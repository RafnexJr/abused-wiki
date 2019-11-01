# Abused Security List

List with my personal collection of "less-known" security related stuff.

- [Abused Security List](#abused-security-list)
  - [Tools](#tools)
    - [Red Teaming](#red-teaming)
    - [Logging](#logging)
    - [Threat Hunting](#threat-hunting)
    - [Incident Response](#incident-response)
    - [Forensics](#forensics)
  - [Resources](#resources)
    - [Hardening & Compliance Lists](#hardening--compliance-lists)
    - [Sample Data](#sample-data)
    - [Wikis & Sites](#wikis--sites)
    - [Whitepapers & Research](#whitepapers--research)
    - [Cheat sheets](#cheat-sheets)
    - [Videos](#videos)
    - [Blogs](#blogs)

## Tools

### Red Teaming

- [Gophish](https://getgophish.com/) - Open Source Phishing Framework
- [Atomic Red Team](https://github.com/redcanaryco/atomic-red-team) - Library of attacks mapped to MITRE to test detection

### Logging

- [EVTXtoELK](https://github.com/dgunter/evtxtoelk) - Python Tool to upload EVTX Logs to Elasticsearch by @dgunter
- [sysmon-config](https://github.com/SwiftOnSecurity/sysmon-config) - Sysmon configuration file template with default high-quality event tracing by @SwiftOnSecurity
- [Sysmon Deployment GPO](https://www.syspanda.com/index.php/2017/02/28/deploying-sysmon-through-gpo/) - Deploy sysmon through active directory group policies
- [auditd-attack](https://github.com/bfuzzy/auditd-attack) - A Linux Auditd rule set mapped to MITRE's Attack Framework by @bfuzzy
- [ThreatHunting Splunk App](https://github.com/olafhartong/ThreatHunting) - A Splunk app mapped to MITRE ATT&CK to guide your threat hunts by @olafhartong
- [Event Forwarding Guidance](https://github.com/olafhartong/Event-Forwarding-Guidance) - Guidance for implementing of security relevant Windows Event Logs by  @olafhartong

### Threat Hunting

- [Detection Lab](https://github.com/clong/DetectionLab) - Lab environment complete with security tooling and logging best practices by @clong
- [Logon Tracer](https://github.com/JPCERTCC/LogonTracer) - Visualize logon inside an active directory by @JPCERTCC
- [RITA](https://github.com/activecm/rita) - Beaconing/DNS tunneling detection and blacklist checking by @activecm
- [Passer](https://www.activecountermeasures.com/free-tools/passer/) - A Passive Sniffer and Inventory Tool by @activecm
- [Klara](https://github.com/KasperskyLab/klara) - Yara testing and developing infrastructure by @KasperskyLab
- [Valhalla](https://valhalla.nextron-systems.com/) - Yara rule database by @Neo23x0

### Incident Response

- [Kansa](https://github.com/davehull/Kansa) - Powershell incident response framework by @davehull

### Forensics

- [PowerForensics](https://powerforensics.readthedocs.io/en/latest/) - Hard Drive forensics analysis
- [Rekall Forensics](http://www.rekall-forensic.com/) - Fork of Volatility from a Google Dude
- [Cold Disk Quick Response Tool](https://github.com/orlikoski/CDQR) - fast and easy to use forensic artifact parsing tool
- [Sigcheck](https://docs.microsoft.com/en-us/sysinternals/downloads/sigcheck) - Sysinternals Tool to check file signatures
- [Cyber Chef](https://github.com/gchq/CyberChef/) - a webapp for encryption, encoding, compression and data analysis

### Malware Analysis

- [Bombox](https://github.com/redcanaryco/atomic-red-team) - Automated setup of Cuckoo sandbox with vagrant by @nbeede 

## Resources

### Hardening & Compliance Lists

- [NSA UEFI Defensive Practicing Guide](https://www.nsa.gov/Portals/70/documents/what-we-do/cybersecurity/professional-resources/ctr-uefi-defensive-practices-guidance.pdf) - Hardening Guide for UEFI Systems
- [Stigviewer](https://www.stigviewer.com/) - Large collection of STIGs available to download
- [DoD Exchange](https://public.cyber.mil/) - US DoD STIG list and other resources
- [Common Controls Hub](https://cch.commoncontrolshub.com) - Create Compliance/Hardening lists based on almost any standards and laws
- [Compliance Dictionary](https://compliancedictionary.com/) - Search engine / dictionary for compliance terms

### Sample Data

- [EVXT Attack Samples](https://github.com/sbousseaden/EVTX-ATTACK-SAMPLES) - Samples of EVTX attack data
- [ThreatLand](https://github.com/threatland) - Scientific malware samples

### Wikis & Sites

- [pwnWiki](http://pwnwiki.io/#!index.md) - Wiki of TTPs after access to system has been gained
- [ADSecurity](https://adsecurity.org/) - Website with various resources for Active Directory Security
- [Red Teaming Experiments](https://ired.team/) - Red teaming experiments wiki
- [OpenSSL Certificate Authority](https://jamielinux.com/docs/openssl-certificate-authority/introduction.html) - Comprehensive guide on how to setup a OpenSSL ca

### Whitepapers & Research

- [JPCert Lateral Movement](https://www.jpcert.or.jp/english/pub/sr/ir_research.html) - Detecting Lateral Movement through Tracking Event Logs
- [Abusing Token Privileges](https://github.com/hatRiot/token-priv)

### Cheat sheets

- [13Cubed Cheatsheets](https://www.13cubed.com/)
- [XSS Cheat Sheet](https://portswigger.net/web-security/cross-site-scripting/cheat-sheet) - contains many vectors that can help you bypass WAFs and filters

### Videos

- [13Cubed Channel](https://www.youtube.com/user/davisrichardg/videos) - Youtube Channel for forensics
- [Video Course: Maleware hunting with Sysinternals tools](https://channel9.msdn.com/events/teched/northamerica/2013/atc-b308#fbid=mb6_bvqq9jj)
- [Yara Rule to find Evolving Malware](https://www.youtube.com/watch?v=XMZ-c2Zwzjg)
- [Black Hills Information Security Youtube Channel](https://www.youtube.com/channel/UCJ2U9Dq9NckqHMbcUupgF0A/featured)

### Blogs

- [Dragos Security Blog](https://dragos.com/blog/)
- [Willi Ballenthin Blog](http://www.williballenthin.com/) - Forensics Blog (Python, EVTX, etc.)
- [One Night in Norfolk](https://norfolkinfosec.com/) - Blog on reverse engineering and malware analysis
