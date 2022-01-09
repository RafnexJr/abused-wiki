List with my personal collection of "less-known" security related stuff.

## Tools

### Red Teaming

- [Gophish](https://getgophish.com/) - Open Source Phishing Framework
- [Atomic Red Team](https://github.com/redcanaryco/atomic-red-team) - Library of attacks mapped to MITRE to test detection
- [Caldera](https://github.com/mitre/caldera) - Automated Red Teaming by MITRE

### Blue Teaming

- [Bluespawn](https://github.com/ION28/BLUESPAWN) - Open Source EDR Client
- [Velociraptor](https://www.velocidex.com/) - Production Ready Open Source EDR Client 

### Logging

- [Elastic Stack Wiki](https://www.peerlyst.com/posts/the-elastic-stack-elk-wiki-chiheb-chebbi?trk=search_page_search_result) - Wiki with a lot of elastic resources.
- [EVTXtoELK](https://github.com/dgunter/evtxtoelk) - Python Tool to upload EVTX Logs to Elasticsearch by @dgunter
- [sysmon-config](https://github.com/SwiftOnSecurity/sysmon-config) - Sysmon configuration file template with default high-quality event tracing by @SwiftOnSecurity
- [Sysmon Deployment GPO](https://www.syspanda.com/index.php/2017/02/28/deploying-sysmon-through-gpo/) - Deploy sysmon through active directory group policies
- [auditd-attack](https://github.com/bfuzzy/auditd-attack) - A Linux AuditD rule set mapped to MITRE's Attack Framework by @bfuzzy
- [ThreatHunting Splunk App](https://github.com/olafhartong/ThreatHunting) - A Splunk app mapped to MITRE ATT&CK to guide your threat hunts by @olafhartong
- [Event Forwarding Guidance](https://github.com/olafhartong/Event-Forwarding-Guidance) - Guidance for implementing of security relevant Windows Event Logs by  @olafhartong

### Threat Hunting

- [Detection Lab](https://github.com/clong/DetectionLab) - Lab environment complete with security tooling and logging best practices by @clong
- [Logon Tracer](https://github.com/JPCERTCC/LogonTracer) - Visualize logon inside an active directory by @JPCERTCC
- [RITA](https://github.com/activecm/rita) - Beaconing/DNS tunneling detection and blacklist checking by @activecm
- [Passer](https://www.activecountermeasures.com/free-tools/passer/) - A Passive Sniffer and Inventory Tool by @activecm
- [Klara](https://github.com/KasperskyLab/klara) - Yara testing and developing infrastructure by @KasperskyLab
- [Valhalla](https://valhalla.nextron-systems.com/) - Yara rule database by @Neo23x0

### Active Defense and Deception

- [Polarbear](https://github.com/polrbearproject/polrbear) - Automated Deception Traps in Python
- [Spidertrap](https://github.com/adhdproject/spidertrap) - HTTP Server that responds with never-ending nested links to confuse web crawlers
- [Portspoof](https://github.com/drk1wi/portspoof) - Responds on every port with Syn+Ack and Service Banner to mess with portscans
- [Cowrie](https://github.com/cowrie/cowrie) - Medium to high interaction honeypot
- [Artillery](https://github.com/BinaryDefense/artillery) - Combination of honeypot, monitoring and alerting system
- [SNARE](https://github.com/mushorg/snare) - Web application honeypot
- [OWA Honeypot](https://github.com/joda32/owa-honeypot) - Honeypot mimicing the Outlook OWA website
- [Cynary Tokens](https://canarytokens.org/generate) - Callback traps to catch attackers
- [Honey Badger](https://bitbucket.org/LaNMaSteR53/honeybadger/src/master/) - Accurate location traceback of attackers even through Tor

### Incident Response

- [Kansa](https://github.com/davehull/Kansa) - Powershell incident response framework by @davehull
- [Nextron Systems](https://www.nextron-systems.com/) - APT Scanners and Yara Rules by @Neo23x0 and his Team

### Forensics

- [PowerForensics](https://powerforensics.readthedocs.io/en/latest/) - Hard Drive forensics analysis
- [Rekall Forensics](http://www.rekall-forensic.com/) - Fork of Volatility from a Google Dude
- [Cold Disk Quick Response Tool](https://github.com/orlikoski/CDQR) - fast and easy to use forensic artifact parsing tool
- [Sigcheck](https://docs.microsoft.com/en-us/sysinternals/downloads/sigcheck) - Sysinternals Tool to check file signatures
- [Cyber Chef](https://github.com/gchq/CyberChef/) - a webapp for encryption, encoding, compression and data analysis

### Malware Analysis

- [Bombox](https://github.com/redcanaryco/atomic-red-team) - Automated setup of Cuckoo sandbox with vagrant by @nbeede

### Ticketing Systems

- [Aurora Incident Response](https://github.com/cyb3rfox/Aurora-Incident-Response) - Graphic IR platform by @cyb3rfox
- [Iris](https://github.com/dfir-iris/iris-web) - Incident Response Investigation System
- [Yeti](https://yeti-platform.github.io/) - Organize threat intelligence
- [FIR](https://github.com/certsocietegenerale/FIR) - Fast Incident Response platform

## Resources

### Hardening & Compliance Lists

- [NSA UEFI Defensive Practicing Guide](https://www.nsa.gov/Portals/70/documents/what-we-do/cybersecurity/professional-resources/ctr-uefi-defensive-practices-guidance.pdf) - Hardening Guide for UEFI Systems
- [Stigviewer](https://www.stigviewer.com/) - Large collection of STIGs available to download
- [DoD Exchange](https://public.cyber.mil/) - US DoD STIG list and other resources
- [Common Controls Hub](https://cch.commoncontrolshub.com) - Create Compliance/Hardening lists based on almost any standards and laws
- [Compliance Dictionary](https://compliancedictionary.com/) - Search engine / dictionary for compliance terms
- [NIST NVD](https://nvd.nist.gov/) - US National Vulnerability Database
- [Risk Forecasting](https://magoo.github.io/Risk-Forecasting/) - Process of risk forecasting and assessment process

### Sample Data

- [EVXT Attack Samples](https://github.com/sbousseaden/EVTX-ATTACK-SAMPLES) - Samples of EVTX attack data
- [ThreatLand](https://github.com/threatland) - Scientific malware samples

### Wikis & Sites

- [pwnWiki](http://pwnwiki.io/#!index.md) - Wiki of TTPs after access to system has been gained
- [ADSecurity](https://adsecurity.org/) - Website with various resources for Active Directory Security
- [Red Teaming Experiments](https://ired.team/) - Red teaming experiments wiki
- [OpenSSL Certificate Authority](https://jamielinux.com/docs/openssl-certificate-authority/introduction.html) - Comprehensive guide on how to setup a OpenSSL ca
- [Threat Hunting Playbooks](https://github.com/hunters-forge/ThreatHunter-Playbook/) - Repository with a lot of awesome threat hunting ressources  
- [Sysmon Security Guide](https://github.com/trustedsec/SysmonCommunityGuide) - Community guide for security relevant sysmon
- [Threat Hunting Framework](https://www.threathunting.net/sqrrl-archive) - Framework for Threat Hunting in your enterprise
- [Securing Priviledge Access](https://docs.microsoft.com/en-us/windows-server/identity/securing-privileged-access/securing-privileged-access-reference-material) - MS Article about priviledge access management
- [MITRE Shield](https://shield.mitre.org/) - MITRE Knowledge base for active defence TTPs
- [13cubed Downloads](https://www.13cubed.com/#downloads)

### Whitepapers & Research

- [JPCert Lateral Movement](https://www.jpcert.or.jp/english/pub/sr/ir_research.html) - Detecting Lateral Movement through Tracking Event Logs
- [Abusing Token Privileges](https://github.com/hatRiot/token-priv) - Research about token priviledge abusing
- [Cyb3rWard0g Presentations](https://github.com/Cyb3rWard0g/presentations) - All presentations made by
- [Secure Operating Systems](https://snikt.net/SecOpS.pdf) - Security aspects of an operating system im German

### Cheat sheets

- [XSS Cheat Sheet](https://portswigger.net/web-security/cross-site-scripting/cheat-sheet) - contains many vectors that can help you bypass WAFs and filters

### Videos

- [13Cubed Channel](https://www.youtube.com/user/davisrichardg/videos) - Youtube Channel for forensics
- [Video Course: Maleware hunting with Sysinternals tools](https://channel9.msdn.com/events/teched/northamerica/2013/atc-b308#fbid=mb6_bvqq9jj)
- [Yara Rule to find Evolving Malware](https://www.youtube.com/watch?v=XMZ-c2Zwzjg)
- [Black Hills Information Security Youtube Channel](https://www.youtube.com/channel/UCJ2U9Dq9NckqHMbcUupgF0A/featured)

### Workshops

- [Elastic SIEM Workshop](https://github.com/mrebeschini/elastic-siem-workshop) - Configure and use the elastic siem
- [Hunters Workshop](https://github.com/HuntersCamp/HuntersWorkshop) . Workshop about creating a basic security platform with open source tools

### Blogs

- [JPMinty](https://www.jaiminton.com/#) - Blog with awesome ressources of blueteam security stuff
- [Dragos Security Blog](https://dragos.com/blog/) - Blog on ICS/OT/SCADA Security
- [Willi Ballenthin Blog](http://www.williballenthin.com/) - Forensics Blog (Python, EVTX, etc.)
- [One Night in Norfolk](https://norfolkinfosec.com/) - Blog on reverse engineering and malware analysis
