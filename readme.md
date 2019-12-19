<div align="center">
	<img width="500" height="350" src="iot_awesome_logo.svg" alt="Awesome">
  <br />
</div>

# Awesome Embedded and IoT Security [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome resources about embedded and IoT security. The list contains software and hardware tools, books, research papers and more.

Botnets like [Mirai](https://en.wikipedia.org/wiki/Mirai_(malware)) have proven that there is a need for more security in embedded and IoT devices. This list shall help beginners and experts to find helpful resources on the topic.  
If you are a beginner, you should have a look at the [Books](#books) and [Case Studies](#case-studies) sections.  
If you want to start right away with your own analysis, you should give the [Analysis Frameworks](#analysis-frameworks) a try.
They are easy to use and you do not need to be an expert to get first meaningful results.

> *Items marked with :euro: are comercial products.*

## Contents

- [Software Tools](#software-tools)
  - [Analysis Frameworks](#analysis-frameworks)
  - [Analysis Tools](#analysis-tools)
  - [Extraction Tools](#extraction-tools)
  - [Support Tools](#support-tools)
- [Hardware Tools](#hardware-tools)
- [Books](#books)
- [Research Papers](#research-papers)
- [Case Studies](#case-studies)
- [Free Training](#free-training)
- [Websites](#websites)
- [Conferences](#conferences)


## Software Tools
Software tools for analyzing embedded/IoT firmware.

### Analysis Frameworks

- [EXPLIoT](https://gitlab.com/expliot_framework/expliot) - Pentest framework like Metasploit but specialized for IoT.
- [FACT - The Firmware Analysis and Comparison Tool](https://fkie-cad.github.io/FACT_core/) - Full-featured static analysis framework including extraction of firmware, analysis utilizing different plug-ins and comparison of different firmware versions.
  - [Improving your firmware security analysis process with FACT](https://passthesalt.ubicast.tv/videos/improving-your-firmware-security-analysis-process-with-fact/) - Conference talk about FACT :tv:.
- [FwAnalyzer](https://github.com/cruise-automation/fwanalyzer) - Analyze security of firmware based on customized rules. Intended as additional step in DevSecOps, similar to CI.

### Analysis Tools

- [Binwalk](https://github.com/ReFirmLabs/binwalk) - Searches a binary for "interesting" stuff.  
- [Firmadyne](https://github.com/firmadyne/firmadyne) - Tries to emulate and pentest a firmware.
- [firmwalker](https://github.com/craigz28/firmwalker) - Searches extracted firmware images for interesting files and information.
- [Firmware Slap](https://github.com/ChrisTheCoolHut/Firmware_Slap) - Discovering vulnerabilities in firmware through concolic analysis and function clustering.
- [Ghidra](https://ghidra-sre.org/) - Software Reverse Engineering suite; handles arbitrary binaries, if you provide CPU architecture and endianness of the binary.
- [Radare2](https://github.com/radare/radare2) - Software Reverse Engineering framework, also handles popular formats and arbitrary binaries, has an extensive command line toolset.
- [Trommel](https://github.com/CERTCC/trommel) - Searches extracted firmware images for interesting files and information.

### Extraction Tools

- [Binwalk](https://github.com/ReFirmLabs/binwalk) - Extracts arbitrary files utilizing a carving approach.
- [FACT Extractor](https://github.com/fkie-cad/fact_extractor) - Detects container format automatically and executes the corresponding extraction tool.
- [Firmware Mod Kit](https://github.com/rampageX/firmware-mod-kit/wiki) - Extraction tools for several container formats.
- [The SRecord package](http://srecord.sourceforge.net/) - Collection of tools for manipulating EPROM files (can convert lots of binary formats).

### Support Tools

- [JTAGenum](https://github.com/cyphunk/JTAGenum) - Add JTAG capabilities to an Arduino.
- [OpenOCD](http://openocd.org/) - Free and Open On-Chip Debugging, In-System Programming and Boundary-Scan Testing.


## Hardware Tools

- [Bus Blaster](http://dangerousprototypes.com/docs/Bus_Blaster) - Detects and interacts with hardware debug ports like [UART](https://en.wikipedia.org/wiki/Universal_asynchronous_receiver-transmitter) and [JTAG](https://en.wikipedia.org/wiki/JTAG).
- [Bus Pirate](http://dangerousprototypes.com/docs/Bus_Pirate) - Detects and interacts with hardware debug ports like UART and JTAG.
- [JTAGULATOR](http://www.grandideastudio.com/jtagulator/) - Detects JTAG Pinouts fast.
- [Saleae](https://www.saleae.com/) - Easy to use Logic Analyzer that support many protocols :euro:.
- [Ikalogic](https://www.ikalogic.com/pages/logic-analyzer-sp-series-sp209) - Alternative to Saleae logic analyzers :euro:.
- [HydraBus](https://hydrabus.com/hydrabus-1-0-specifications/) -  Open source multi-tool hardware similar to the BusPirate but with NFC capabilities.
- [ChipWhisperer](https://newae.com/tools/chipwhisperer/) - Detects Glitch/Side-channel attacks.
- [Glasgow](https://github.com/GlasgowEmbedded/Glasgow) -  Tool for exploring and debugging different digital interfaces.
- [J-Link](https://www.segger.com/products/debug-probes/j-link/models/model-overview/) - J-Link offers USB powered JTAG debug probes for multiple different CPU cores :euro:.


## Books

- 2020, Jasper van Woudenberg, Colin O'Flynn: [The Hardware Hacking Handbook: Breaking Embedded Security with Hardware Attacks](https://www.amazon.com/Hardware-Hacking-Handbook-Breaking-Embedded-ebook/dp/B077WZBFYL)
- 2019, Yago Hansen: [The Hacker's Hardware Toolkit: The best collection of hardware gadgets for Red Team hackers, Pentesters and security researchers](https://www.amazon.com/Hackers-Hardware-Toolkit-collection-researchers/dp/1099209463)
- 2019, Aditya Gupta: [The IoT Hacker's Handbook: A Practical Guide to Hacking the Internet of Things](https://www.apress.com/us/book/9781484242995)
- 2018, Mark Swarup Tehranipoor: [Hardware Security: A Hands-on Learning Approach](https://www.elsevier.com/books/hardware-security/bhunia/978-0-12-812477-2)
- 2017, Aditya Gupta, Aaron Guzman: [IoT Penetration Testing Cookbook](https://www.packtpub.com/networking-and-servers/iot-penetration-testing-cookbook)  
- 2017, Andrew Huang: [The Hardware Hacker: Adventures in Making and Breaking Hardware](https://nostarch.com/hardwarehackerpaperback)
- 2016, Craig Smith: [The Car Hacker's Handbook: A Guide for the Penetration Tester](https://nostarch.com/carhacking)
- 2015, Nitesh Dhanjan: [Abusing the Internet of Things: Blackouts, Freakouts, and Stakeouts](https://shop.oreilly.com/product/0636920033547.do)
- 2014, Debdeep Mukhopadhyay: [Hardware Security: Design, Threats, and Safeguards](https://www.taylorfrancis.com/books/9780429066900)
- 2014, Jack Ganssle: [The Firmware Handbook (Embedded Technology)](https://www.elsevier.com/books/the-firmware-handbook/ganssle/978-0-7506-7606-9)
- 2013, Andrew Huang: [Hacking the XBOX](https://nostarch.com/xboxfree)



## Research Papers
<!--lint ignore match-punctuation-->
- 2019, Alrawi et al: [SoK: Security Evaluation of Home-Based IoT Deployments](https://alrawi.github.io/static/papers/alrawi_sok_sp19.pdf)
- 2019, Abbasi et al: [Challenges in Designing Exploit Mitigations for Deeply Embedded Systems](https://ieeexplore.ieee.org/abstract/document/8806725)
- 2019, Song et al: [PeriScope: An Effective Probing and Fuzzing Framework for the Hardware-OS Boundary](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_04A-1_Song_paper.pdf)
- 2018, Muench et al: [What You Corrupt Is Not What You Crash: Challenges in Fuzzing Embedded Devices](http://www.eurecom.fr/en/publication/5417/download/sec-publi-5417.pdf)
- 2017, O'Meara et al: [Embedded Device Vulnerability Analysis Case Study Using Trommel](https://resources.sei.cmu.edu/library/asset-view.cfm?assetid=509271)
- 2017, Jacob et al: [How to Break Secure Boot on FPGA SoCs through Malicious Hardware](https://eprint.iacr.org/2017/625.pdf)
- 2017, Costin et al: [Towards Automated Classification of Firmware Images and Identification of Embedded Devices](http://s3.eurecom.fr/docs/ifip17_costin.pdf)
- 2016, Kammerstetter et al: [Embedded Security Testing with Peripheral Device Caching and Runtime Program State Approximation](http://www.seclab.tuwien.ac.at/papers/kammerstetter_secuware2016_peripheralCache.pdf)
- 2016, Chen et al: [Towards Automated Dynamic Analysis for Linux-based Embedded Firmware](https://www.dcddcc.com/docs/2016_paper_firmadyne.pdf)
- 2016, Costin et al: [Automated Dynamic Firmware Analysis at Scale: A Case Study on Embedded Web Interfaces](http://s3.eurecom.fr/docs/asiaccs16_costin.pdf)
- 2015, Shoshitaishvili et al:[Firmalice - Automatic Detection of Authentication Bypass Vulnerabilities in Binary Firmware](https://seclab.cs.ucsb.edu/media/uploads/papers/firmalice.pdf)
- 2015, Papp et al: [Embedded Systems Security: Threats, Vulnerabilities, and Attack Taxonomy](http://www.cse.psu.edu/~pdm12/cse597g-f15/readings/cse597g-embedded_systems.pdf)
- 2014, Zaddach et al: [Avatar: A Framework to Support Dynamic Security Analysis of Embedded Systems' Firmwares](http://www.eurecom.fr/en/publication/4158/download/rs-publi-4158.pdf)
- 2014, Alimi et al: [Analysis of embedded applications by evolutionary fuzzing](http://ieeexplore.ieee.org/document/6903734/)
- 2014, Costin et al: [A Large-Scale Analysis of the Security of Embedded Firmware
s](http://www.s3.eurecom.fr/docs/usenixsec14_costin.pdf)
- 2013, Davidson et al: [FIE on Firmware: Finding Vulnerabilities in Embedded Systems using Symbolic Execution](https://www.usenix.org/system/files/conference/usenixsecurity13/sec13-paper_davidson.pdf)

## Case Studies
<!--lint ignore no-repeat-punctuation-->
- [Binary Hardening in IoT products](https://cyber-itl.org/2019/08/26/iot-data-writeup.html)
- [Deadly Sins Of Development](https://youtu.be/nXyglaY9N9w) - Conference talk presenting several real world examples on real bad implementations :tv:.
- [Hacking the DSP-W215, Again](http://www.devttys0.com/2014/05/hacking-the-dspw215-again/)
- [Multiple vulnerabilities found in the D-link DWR-932B](https://pierrekim.github.io/blog/2016-09-28-dlink-dwr-932b-lte-routers-vulnerabilities.html)
- [Pwning the Dlink 850L routers and abusing the MyDlink Cloud protocol](https://pierrekim.github.io/blog/2017-09-08-dlink-850l-mydlink-cloud-0days-vulnerabilities.html)
- [PWN Xerox Printers (...again)](https://www.fkie.fraunhofer.de/content/dam/fkie/de/documents/xerox_phaser_6700_white_paper.pdf)


## Free Training

- [Hardware Hacking 101](https://github.com/rdomanski/hardware_hacking/tree/master/my_talks/Hardware_Hacking_101) - Workshop @ BSides Munich 2019.
- [IoTGoat](https://github.com/scriptingxss/IoTGoat) - IoTGoat is a deliberately insecure firmware based on OpenWrt.
- [Rhme-2017/2018](https://github.com/Riscure/Rhme-2017) - Riscure Hack Me 3 embedded hardware CTF 2017-2018.
- [Rhme-2016](https://github.com/Riscure/Rhme-2016) - Riscure Hack me 2 is a low level hardware CTF challenge.
- [Rhme-2015](https://github.com/Riscure/RHme-2015) - First riscure Hack me hardware CTF challenge.
- [Embedded Security CTF](https://microcorruption.com) - Microcorruption: Embedded Security CTF.


## Websites

- [OWASP Embedded Application Security Project](https://www.owasp.org/index.php/OWASP_Embedded_Application_Security) - Development best practices and list of hardware and software tools.
- [OWASP Internet of Things Project](https://www.owasp.org/index.php/OWASP_Internet_of_Things_Project) - IoT common vulnerabilities and attack surfaces. 
- [Hacking Printers Wiki](http://hacking-printers.net/wiki/index.php/Main_Page)
- [Router Passwords](https://www.routerpasswords.com) - Default login credential database sorted by manufacturer.

## Conferences
Conferences focused on embedded and/or IoT security.

- [Hardwear.io](https://hardwear.io/) - The Hague, September.
- [Hardwear.io USA](https://hardwear.io/) - Santa Clara, June. 

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Fraunhofer FKIE has waived all copyright and
related or neighboring rights to this work.
