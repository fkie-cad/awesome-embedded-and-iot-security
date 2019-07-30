# Awesome Embedded and IoT Security [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome resources about embedded and IoT security. The list contains software and hardware tools, books, research papers and more.

If you are a beginner, you should have a look at the [Books](#books) and [Case Studies](#case-studies) sections.  
If you want to start right away with your own analysis, you should give the [Analysis Frameworks](#analysis-frameworks) a try.
They are easy to use and you do not need to be an expert to get first meaningful results.

## Contents

- [Software Tools](#software-tools)
  - [Analysis Frameworks](#analysis-frameworks)
  - [Analysis Tools](#analysis-tools)
  - [Extraction Tools](#extraction-tools)
- [Hardware Tools](#hardware-tools)
- [Books](#books)
- [Research Papers](#research-papers)
  - [Case Studies](#case-studies)
- [Open source trainings](#free-trainings)
- [Websites](#websites)
- [Conferences](#conferences)

## Software Tools
Software tools for analyzing embedded/IoT firmware.

### Analysis Frameworks

- [FACT - The Firmware Analysis and Comparison Tool](https://fkie-cad.github.io/FACT_core/) - Full-featured static analysis framework including extraction of firmware, analysis utilizing different plug-ins and comparison of different firmware versions.
- [EXPLIoT](https://gitlab.com/expliot_framework/expliot) - Pentest framework like Metasploit but specialized for IoT.

### Analysis Tools

- [Binwalk](https://github.com/ReFirmLabs/binwalk) - Searches a binary for "interesting" stuff.  
- [Firmadyne](https://github.com/firmadyne/firmadyne) - Tries to emulate and pentest a firmware.
- [firmwalker](https://github.com/craigz28/firmwalker) - Searches extracted firmware images for interesting files and information.
- [Ghidra](https://ghidra-sre.org/) - Software Reverse Engineering suite; handles arbitrary binaries, if you provide CPU architecture and endianness of the binary.
- [Trommel](https://github.com/CERTCC/trommel) - Searches extracted firmware images for interesting files and information.

### Support Tools

- [JTAGenum](https://github.com/cyphunk/JTAGenum) - Add JTAG capabilities to an Arduino
- [OpenOCD](https://http://openocd.org/) - Free and Open On-Chip Debugging, In-System Programming and Boundary-Scan Testing

### Extraction Tools

- [Binwalk](https://github.com/ReFirmLabs/binwalk) - Extracts arbitrary files utilizing a carving approach.
- [FACT Extractor](https://github.com/fkie-cad/fact_extractor) - Detects container format automatically and executes the corresponding extraction tool.
- [Firmware Mod Kit](https://github.com/rampageX/firmware-mod-kit/wiki) - Extraction tools for several container formats.

## Hardware Tools

- [Bus Blaster](http://dangerousprototypes.com/docs/Bus_Blaster) - Detects and interacts with hardware debug ports like [UART](https://en.wikipedia.org/wiki/Universal_asynchronous_receiver-transmitter) and [JTAG](https://en.wikipedia.org/wiki/JTAG).
- [Bus Pirate](http://dangerousprototypes.com/docs/Bus_Pirate) - Detects and interacts with hardware debug ports like UART and JTAG.
- [JTAGULATOR](http://www.grandideastudio.com/jtagulator/) - Detects JTAG Pinouts fast.
- [Saleae](https://www.saleae.com/) - Easy to use Logic Analyzer that support many protocols. :euro:
- [Ikalogic](https://www.ikalogic.com/pages/logic-analyzer-sp-series-sp209) - Alternative to Saleae logic analyzers
- [HydraBus](https://hydrabus.com/hydrabus-1-0-specifications/) -  Open source multi-tool hardware similar to the BusPirate but with NFC capabilities 
- [ChipWhisperer](https://newae.com/tools/chipwhisperer/) - Detects Glitch/Side-channel attacks 
- [Glasgow](https://github.com/GlasgowEmbedded/Glasgow) -  Tool for exploring and debugging different digital interfaces
- [J-Link](https://www.segger.com/products/debug-probes/j-link/models/model-overview/) - J-Link offers USB powered JTAG debug probes for multiple different CPU cores


## Books

- 2020, Jasper van Woudenberg, Colin O'Flynn: [The Hardware Hacking Handbook: Breaking Embedded Security with Hardware Attacks](https://www.amazon.com/Hardware-Hacking-Handbook-Breaking-Embedded-ebook/dp/B077WZBFYL)
- 2019 Yago Hansen: [The Hacker's Hardware Toolkit: The best collection of hardware gadgets for Red Team hackers, Pentesters and security researchers](https://www.amazon.com/Hackers-Hardware-Toolkit-collection-researchers/dp/1099209463)
- 2019, Aditya Gupta: [The IoT Hacker's Handbook: A Practical Guide to Hacking the Internet of Things](https://www.apress.com/us/book/9781484242995)
- 2018, Mark Swarup Tehranipoor: [Hardware Security: A Hands-on Learning Approach](https://www.amazon.com/Hardware-Security-Hands-Learning-Approach/dp/0128124776)
- 2017, Aditya Gupta, Aaron Guzman: [IoT Penetration Testing Cookboo](https://www.packtpub.com/networking-and-servers/iot-penetration-testing-cookbook)  
- 2017, Andrew Huang: [The Hardware Hacker: Adventures in Making and Breaking Hardware](https://www.amazon.com/Hardware-Hacker-Adventures-Making-Breaking/dp/159327758X)
- 2016, Craig Smith: [The Car Hacker's Handbook: A Guide for the Penetration Tester](https://www.amazon.com/Car-Hackers-Handbook-Penetration-Tester/dp/1593277032)
- 2015, Nitesh Dhanjan: [Abusing the Internet of Things: Blackouts, Freakouts, and Stakeouts](https://www.amazon.in/Abusing-Internet-Things-Blackouts-Freakouts-ebook/dp/B013VQ7N36)
- 2014, Debdeep Mukhopadhyay: [Hardware Security: Design, Threats, and Safeguards](https://www.amazon.com/Hardware-Security-Design-Threats-Safeguards/dp/143989583X)
- 2014, Jack Ganssle: [The Firmware Handbook (Embedded Technology)](https://www.amazon.com/Firmware-Handbook-Embedded-Technology/dp/075067606X)
- 2013, Andrew Huang: [Hacking the XBOX](https://nostarch.com/xboxfree)
- 2007, Paul Asadoorian, Larry Pesce: [Linksys WRT54G Ultimate Hacking](https://www.amazon.com/Linksys-WRT54G-Ultimate-Hacking-Asadoorian/dp/1597491667)
- 2004, Joe Grand, Kevin Mitnick, Ryan Russel: [Hardware Hacking: Have Fun While Voiding Your Warranty](https://www.amazon.com/Hardware-Hacking-While-Voiding-Warranty/dp/1932266836)


## Research Papers

- 2018, Muench et al: [What You Corrupt Is Not What You Crash: Challenges in Fuzzing Embedded Devices](http://www.eurecom.fr/en/publication/5417/download/sec-publi-5417.pdf)
- 2017, Jacob et al: [How to Break Secure Boot on FPGA SoCs through Malicious Hardware](https://eprint.iacr.org/2017/625.pdf)
- 2017, Costin et al: [Towards Automated Classification of Firmware Images and Identification of Embedded Devices](http://s3.eurecom.fr/docs/ifip17_costin.pdf)
- 2016, Kammerstetter et al: [Embedded Security Testing with Peripheral Device Caching and Runtime Program State Approximation](http://www.seclab.tuwien.ac.at/papers/kammerstetter_secuware2016_peripheralCache.pdf)
- 2016, Chen et al: [Towards Automated Dynamic Analysis for Linux-based Embedded Firmware](https://www.dcddcc.com/docs/2016_paper_firmadyne.pdf)
- 2016, Costin et al: [Automated Dynamic Firmware Analysis at Scale: A Case Study on Embedded Web Interfaces](http://s3.eurecom.fr/docs/asiaccs16_costin.pdf)
- 2015, Shoshitaishvili et al:[Firmalice - Automatic Detection of Authentication Bypass Vulnerabilities in Binary Firmware](https://seclab.cs.ucsb.edu/media/uploads/papers/firmalice.pdf)
- 2015, Papp et al: [Embedded Systems Security: Threats, Vulnerabilities, and Attack Taxonomy](http://www.cse.psu.edu/~pdm12/cse597g-f15/readings/cse597g-embedded_systems.pdf)
- 2014, Zaddach et al: [Avatar: A Framework to Support Dynamic Security Analysis of Embedded Systems’ Firmwares](http://www.eurecom.fr/en/publication/4158/download/rs-publi-4158.pdf)
- 2014, Alimi et al: [Analysis of embedded applications by evolutionary fuzzing](http://ieeexplore.ieee.org/document/6903734/)
- 2014, Costin et al: [A Large-Scale Analysis of the Security of Embedded Firmware
s](http://www.s3.eurecom.fr/docs/usenixsec14_costin.pdf)
- 2013, Davidson et al: [FIE on Firmware: Finding Vulnerabilities in Embedded Systems using Symbolic Execution](https://www.usenix.org/system/files/conference/usenixsecurity13/sec13-paper_davidson.pdf)

### Case Studies

- [Hacking the DSP-W215, Again](http://www.devttys0.com/2014/05/hacking-the-dspw215-again/)
- [Multiple vulnerabilities found in the D-link DWR-932B](https://pierrekim.github.io/blog/2016-09-28-dlink-dwr-932b-lte-routers-vulnerabilities.html)
- [Pwning the Dlink 850L routers and abusing the MyDlink Cloud protocol](https://pierrekim.github.io/blog/2017-09-08-dlink-850l-mydlink-cloud-0days-vulnerabilities.html)
- [PWN Xerox Printers (...again)](https://www.fkie.fraunhofer.de/content/dam/fkie/de/documents/xerox_phaser_6700_white_paper.pdf)


## Free Trainings

- [Hardware Hacking 101](https://github.com/rdomanski/hardware_hacking/tree/master/my_talks/Hardware_Hacking_101) - Workshop @ BSides Munich 2019
- [IoTGoat](https://github.com/scriptingxss/IoTGoat) - IoTGoat is a deliberately insecure firmware based on OpenWrt
- [Rhme-2017/2018](https://github.com/Riscure/Rhme-2017) - Riscure Hack Me 3 embedded hardware CTF 2017-2018
- [Rhme-2016](https://github.com/Riscure/Rhme-2016) - Riscure Hack me 2 is a low level hardware CTF challenge
- [Rhme-2015](https://github.com/Riscure/RHme-2015) - First riscure Hack me hardware CTF challenge
- [Embedded Security CTF](https://microcorruption.com/login) - Microcorruption: Embedded Security CTF


## Websites

- [OWASP Embedded Application Security](https://www.owasp.org/index.php/OWASP_Embedded_Application_Security)
- [OWASP Internet of Things Project](https://www.owasp.org/index.php/OWASP_Internet_of_Things_Project)
- [Hacking Printers Wiki](http://hacking-printers.net/wiki/index.php/Main_Page)
- [Router Passwords](https://www.routerpasswords.com) - Default login credential database sorted by manufacturer.

## Conferences

- [Hardwear.io](https://hardwear.io/)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Fraunhofer FKIE has waived all copyright and
related or neighboring rights to this work.
