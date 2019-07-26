# Awesome Embedded and IoT Security [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources about embedded and IoT security. The list contains software and hardware tools, books, research papers and more. 


## Contents

- [Software Tools](#software-tools)
  - [Analysis Frameworks](#analysis-frameworks)
  - [Analysis Tools](#analysis-tools)
  - [Extraction Tools](#extraction-tools)
- [Hardware Tools](#hardware-tools)
- [Books](#books)
- [Research Papers](#research-papers)
  - [Case Studies](#case-studies)
- [Websites](#websites)
- [Conferences](#conferences)

## Software Tools
Software Tools for analyzing embedded firmware images.

### Analysis Frameworks

- [FACT - The Firmware Analysis and Comparison Tool](https://fkie-cad.github.io/FACT_core/) - Full featured static analysis framework including extraction of firmware, analysis utilizing different plug-ins and comparison of different firmware versions.
- [EXPLIoT](https://gitlab.com/expliot_framework/expliot) - Pentest framework like Metasploit but specialized for IoT.

### Analysis Tools

- [Binwalk](https://github.com/ReFirmLabs/binwalk) - Searches a binary for "interesting" stuff.  
- [Firmadyne](https://github.com/firmadyne/firmadyne) - Tries to emulate and pentest a firmware.
- [firmwalker](https://github.com/craigz28/firmwalker) - Searches extracted firmware images for interesting files and information.
- [Trommel](https://github.com/CERTCC/trommel) - Searches extracted firmware images for interesting files and information.

### Extraction Tools

- [Binwalk](https://github.com/ReFirmLabs/binwalk) - Extracts arbitrary files utilizing a carving approach.
- [FACT Extractor](https://github.com/fkie-cad/fact_extractor) - Detects container format automatically and executes the corresponding extraction tool.
- [Firmware Mod Kit](https://github.com/rampageX/firmware-mod-kit/wiki) - Extraction tools for several container formats.

## Hardware Tools

- [Bus Blaster](http://dangerousprototypes.com/docs/Bus_Blaster) - Detects and interacts with hardware debug ports like UART and JTAG.
- [Bus Pirate](http://dangerousprototypes.com/docs/Bus_Pirate) - Detects and interacts with hardware debug ports like UART and JTAG.
- [JTAGULATOR](http://www.grandideastudio.com/jtagulator/) - Detects JTAG Pinouts.


## Books

- 2019, Aditya Gupta: [The IoT Hacker's Handbook: A Practical Guide to Hacking the Internet of Things](https://www.apress.com/us/book/9781484242995)

## Research Papers

- 2018, Muench et al: [What You Corrupt Is Not What You Crash: Challenges in Fuzzing Embedded Devices](http://www.eurecom.fr/en/publication/5417/download/sec-publi-5417.pdf)
- 2017, nsr: [Avatar 2: Towards an open source binary firmware analysis framework](https://media.ccc.de/v/34c3-9195-avatar)
- 2017, Costin et al: [Towards Automated Classification of Firmware Images and Identification of Embedded Devices](http://s3.eurecom.fr/docs/ifip17_costin.pdf)
- 2016, Kammerstetter et al: [Embedded Security Testing with Peripheral Device Caching and Runtime Program State Approximation](http://www.seclab.tuwien.ac.at/papers/kammerstetter_secuware2016_peripheralCache.pdf)
- 2016, Chen et al: [Towards Automated Dynamic Analysis for Linux-based Embedded Firmware](https://www.dcddcc.com/docs/2016_paper_firmadyne.pdf)
- 2016, Costin et al: [Automated Dynamic Firmware Analysis at Scale: A Case Study on Embedded Web Interfaces](http://s3.eurecom.fr/docs/asiaccs16_costin.pdf)
- 2015, Gascon et al: [PULSAR: Stateful Black-Box Fuzzing of Proprietary Network Protocols](https://www.sec.cs.tu-bs.de/pubs/2015-securecomm.pdf)
- 2015, Shoshitaishvili et al:[Firmalice - Automatic Detection of Authentication Bypass Vulnerabilities in Binary Firmware](https://seclab.cs.ucsb.edu/media/uploads/papers/firmalice.pdf)
- 2015, Papp et al: [Embedded Systems Security: Threats, Vulnerabilities, and Attack Taxonomy](http://www.cse.psu.edu/~pdm12/cse597g-f15/readings/cse597g-embedded_systems.pdf)
- 2014, Zaddach et al: [Avatar: A Framework to Support Dynamic Security Analysis of Embedded Systems’ Firmwares](http://www.eurecom.fr/en/publication/4158/download/rs-publi-4158.pdf)
- 2014, Alimi et al: [Analysis of embedded applications by evolutionary fuzzing](http://ieeexplore.ieee.org/document/6903734/)
- 2014, Costin et al: [A Large-Scale Analysis of the Security of Embedded Firmware
s](http://www.s3.eurecom.fr/docs/usenixsec14_costin.pdf)
- 2013, Davidson et al: [FIE on Firmware: Finding Vulnerabilities in Embedded Systems using Symbolic Execution](https://www.usenix.org/system/files/conference/usenixsecurity13/sec13-paper_davidson.pdf)

### Case Studies

Case Studies are a good start to learn how to find a vulnerabilities in embedded firmware.

- [Hacking the DSP-W215, Again](http://www.devttys0.com/2014/05/hacking-the-dspw215-again/)
- [Multiple vulnerabilities found in the Dlink DWR-932B](https://pierrekim.github.io/blog/2016-09-28-dlink-dwr-932b-lte-routers-vulnerabilities.html)
- [Pwning the Dlink 850L routers and abusing the MyDlink Cloud protocol](https://pierrekim.github.io/blog/2017-09-08-dlink-850l-mydlink-cloud-0days-vulnerabilities.html)
- [PWN Xerox Printers (...again)](https://www.fkie.fraunhofer.de/content/dam/fkie/de/documents/xerox_phaser_6700_white_paper.pdf)

## Websites

- [OWASP Embedded Application Security](https://www.owasp.org/index.php/OWASP_Embedded_Application_Security)
- [OWASP Internet of Things Project](https://www.owasp.org/index.php/OWASP_Internet_of_Things_Project)

## Conferences

- [Hardwear.io](https://hardwear.io/)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Fraunhofer FKIE has waived all copyright and
related or neighboring rights to this work.
