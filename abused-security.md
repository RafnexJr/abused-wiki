# Abused Security List

List with my personal collection of "less-known" security related stuff.

## Content

- [Abused Security List](#abused-security-list)
  - [Content](#content)
  - [Tools](#tools)
    - [Logging and Threat Hunting](#logging-and-threat-hunting)
    - [Yara Rules](#yara-rules)
    - [Network Analysis](#network-analysis)
    - [Stegography](#stegography)
    - [Disk Analysis](#disk-analysis)
    - [Memory Analysis](#memory-analysis)
    - [Timeline Tools](#timeline-tools)
    - [Malware Discovery/Scanning](#malware-discoveryscanning)
    - [Log Analysis](#log-analysis)
  - [Resources](#resources)
    - [Hardening](#hardening)
    - [Compliance](#compliance)
    - [Tactics, Techniques and Procedures](#tactics-techniques-and-procedures)
    - [Exploit Research](#exploit-research)
    - [Threat Hunting](#threat-hunting)
    - [Logging](#logging)
    - [Cheatsheets](#cheatsheets)
    - [Videos](#videos)
    - [Blogs](#blogs)

## Tools

### Logging and Threat Hunting

- [sysmon-config](https://github.com/SwiftOnSecurity/sysmon-config) - Sysmon configuration file template with default high-quality event tracing
- [Sysmon Deployment GPO](https://www.syspanda.com/index.php/2017/02/28/deploying-sysmon-through-gpo/)
- [auditd-attack](https://github.com/bfuzzy/auditd-attack) - A Linux Auditd rule set mapped to MITRE's Attack Framework
- [ThreatHunting Splunk App](https://github.com/olafhartong/ThreatHunting) - A Splunk app mapped to MITRE ATT&CK to guide your threat hunts
- [Detection Lab](https://github.com/clong/DetectionLab) - Lab environment complete with security tooling and logging best practices
- [Event Forwarding Guidance](https://github.com/olafhartong/Event-Forwarding-Guidance) - Guidance for implementing of security relevant Windows Event Logs

### Yara Rules

- [Klara](https://github.com/KasperskyLab/klara) - Yara testing and developing infrastructre by Kaspersky

### Network Analysis

- [RITA](https://github.com/activecm/rita) - Beaconing/DNS tunneling detection and blacklist checking
- [Passer](https://www.activecountermeasures.com/free-tools/passer/) - A Passive Sniffer and Inventory Tool

### Stegography

- [StegHide](http://steghide.sourceforge.net/) - Tool for Steganography in images and audio files.

### Disk Analysis

- [Autopsy](https://www.sleuthkit.org/autopsy/) - Timeline Analysis, Keyword Search, Artifact recovery, Disk analysis, etc.
- [Sleuth Kit](https://www.sleuthkit.org/sleuthkit/) - Volume and FS Analysis, History, etc.
- [PowerForensics](https://powerforensics.readthedocs.io/en/latest/) - Hard Drive forensics analysis

### Memory Analysis

- [Redline](https://www.fireeye.com/services/freeware/redline.html) - Mamory analysis for running machine
- [Volatility Framework](https://www.volatilityfoundation.org/26) Memory Forensics, Atrifact Extraction
- [Rekall Forensics](http://www.rekall-forensic.com/) - Fork of Volatility from a Google Dude

### Timeline Tools

- [log2timeline / plaso](https://plaso.readthedocs.io/en/latest/) - Artifact timeline creation and analysis
- [Bulk Extractor](https://github.com/simsong/bulk_extractor) - Extracts data like URL, Telephone and JPEGS from Disk Image
- [Cold Disk Quick Response Tool](https://github.com/orlikoski/CDQR) - fast and easy to use forensic artifact parsing tool

### Malware Discovery/Scanning

- [FireEye Labs Obfuscated String Solver](https://github.com/fireeye/flare-floss) -  Automatically extract obfuscated strings from malware
- [Malware Byte](https://www.malwarebytes.com/) - Maleware scanner
- [Sigcheck](https://docs.microsoft.com/en-us/sysinternals/downloads/sigcheck) - Sysinternals Tool to check file signatures

### Log Analysis

- [EVTXtoELK](https://github.com/dgunter/evtxtoelk) - Python Tool to upload EVTX Logs to Elasticsearch

## Resources

### Hardening

- [NSA UEFI Defensive Practicing Guide](https://www.nsa.gov/Portals/70/documents/what-we-do/cybersecurity/professional-resources/ctr-uefi-defensive-practices-guidance.pdf) - Hardening Guide for UEFI Systems
- [Stigviewer](https://www.stigviewer.com/) - Large collection of STIGs availbe to download
- [DoD Exchange](https://public.cyber.mil/) - US DoD STIG list and other ressources

### Compliance

- [Common Controls Hub](https://cch.commoncontrolshub.com) - Create Compliance/Hardening lists based on almost any standards and laws
- [Compliance Dictionary](https://compliancedictionary.com/) - Search engine / dictionary for compliance terms

### Tactics, Techniques and Procedures

- [pwnWiki](http://pwnwiki.io/#!index.md) - Wiki of TTPs after access to system has been gained

### Exploit Research

- [Exploit DB](https://www.exploit-db.com/) - Database of known exploits

### Threat Hunting

- [Valhalla](https://valhalla.nextron-systems.com/) - Yara rule database

### Logging

- [JPCert Lateral Movement](https://www.jpcert.or.jp/english/pub/sr/ir_research.html) - Detecting Lateral Movement through Tracking Event Logs

### Cheatsheets

- [13Cubed Cheatsheets](https://www.13cubed.com/)

### Videos

- [13Cubed  Channel](https://www.youtube.com/user/davisrichardg/videos)
- [Video Course: Maleware hunting with Sysinternals tools](https://channel9.msdn.com/events/teched/northamerica/2013/atc-b308#fbid=mb6_bvqq9jj)
- [Yara Rule to find Evolving Malware](https://www.youtube.com/watch?v=XMZ-c2Zwzjg)
- [Black Hills Information Security Youtube Channel](https://www.youtube.com/channel/UCJ2U9Dq9NckqHMbcUupgF0A/featured)

### Blogs

- [Dragos Security Blog](https://dragos.com/blog/)
- [Willi Ballenthin Blog](http://www.williballenthin.com/) - Forensics Blog (Python, EVTX, etc.)
