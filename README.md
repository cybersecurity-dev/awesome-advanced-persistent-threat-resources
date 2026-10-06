<div align="center">

```mermaid
mindmap
  root((APT<br/>Kill Chain))
    Reconnaissance
      OSINT
      Social Engineering
      Employee Profiling
    
    Resource Development
      Domains
      C2 Servers
      Malware Creation

    Initial Access
      Phishing
      Exploit
      Supply Chain

    Persistence
      Registry Keys
      Scheduled Tasks
      Services

    Privilege Escalation
      Exploits
      Token Abuse

    Defense Evasion
      Obfuscation
      Living-Off-The-Land
      Process Injection

    Credential Access
      Keylogging
      LSASS Dumping
      Browser Credentials

    Discovery
      Host Discovery
      Network Discovery
      Account Discovery

    Lateral Movement
      RDP
      SMB
      PsExec

    Collection
      Documents
      Databases
      Emails

    Command and Control
      HTTPS
      DNS
      TOR
      Cloud Services

    Exfiltration
      Encryption
      Compression
      Covert Channels

    Impact
      Espionage
      Sabotage
      Destruction
```

# Awesome Advanced Persistent Threat ([_APT_](https://wikipedia.org/wiki/Advanced_persistent_threat)) Resources [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
</div>

[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)]()
[![Windows](https://custom-icon-badges.demolab.com/badge/Windows-0078D6?style=for-the-badge&logo=windows11&logoColor=white)]()
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)](https://www.reddit.com/r/APT/new/) 
[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtube.com/playlist?list=PL9V4Zu3RroiUdIxgc5RQhYLn0hDXe5PlQ&si=_3KZeEetpOg1mMQw)

<p align="center">
    <a href="https://github.com/cybersecurity-dev/"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/github.svg" alt="GitHub"></a>
    &nbsp;
    <a href="https://www.youtube.com/@CyberThreatDefense"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/youtube.svg" alt="YouTube"></a>
    &nbsp;
    <a href="https://cyberthreatdefence.com/my_awesome_lists"><img height="20" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/blog.svg" alt="My Awesome Lists"></a>
    <img src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/bar.gif">
</p>

```mermaid
flowchart TD
    
    A[Strategic Objective]
    
    A --> B[Target Selection]
    B --> C[Reconnaissance]

    C --> C1[OSINT Collection]
    C --> C2[Employee Profiling]
    C --> C3[Network Footprinting]

    C --> D[Resource Development]

    D --> D1[Malware Development]
    D --> D2[C2 Infrastructure Setup]
    D --> D3[Domain Registration]

    D --> E[Initial Access]

    E --> E1[Spear Phishing]
    E --> E2[Exploit Vulnerability]
    E --> E3[Supply Chain Attack]

    E --> F[Execution]

    F --> G[Persistence]

    G --> G1[Backdoor Installation]
    G --> G2[Scheduled Tasks]
    G --> G3[Registry Modification]

    G --> H[Privilege Escalation]

    H --> I[Defense Evasion]

    I --> J[Credential Access]

    J --> K[Discovery]

    K --> K1[Host Discovery]
    K --> K2[Network Discovery]
    K --> K3[Account Discovery]

    K --> L[Lateral Movement]

    L --> M[Collection]

    M --> N[Command & Control]

    N --> O[Data Exfiltration]

    O --> P[Mission Objective]

    P --> P1[Cyber Espionage]
    P --> P2[Intellectual Property Theft]
    P --> P3[Critical Infrastructure Disruption]

    P --> Q[Maintain Long-Term Presence]

    Q --> J

    style A fill:#d5e8d4
    style P fill:#ffe6cc
    style O fill:#f8cecc
    style N fill:#dae8fc
```

## 📖 Contents
- [Books](#books)
- [Videos](#videos)
- [Blogs](#blogs)
- [My Other Awesome Lists](#my-other-awesome-lists)
- [Contributing](#contributing)
- [Contributors](#contributors)


## Books
- [Advanced Cyber Threat Intelligence and Hunting](https://www.amazon.com/Advanced-Cyber-Threat-Intelligence-Hunting/dp/1806380390)
- [Attribution of Advanced Persistent Threats](https://www.amazon.com/Attribution-Advanced-Persistent-Threats-Cyber-Espionage-ebook/dp/B08DCL8X8L/)

## Videos

## Blogs
- [APT Groups Encyclopedia | `Complete Threat Intelligence DB`](https://cyllex.io/encyclopedia/)
- [MITRE ATT\&CK - APT Groups](https://attack.mitre.org/groups/)

##

### My Other Awesome Lists
You can access the my other awesome lists [here](https://cyberthreatdefence.com/my_awesome_lists)

### Contributing
[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors
[Thanks goes to these contributors](https://github.com/cybersecurity-dev/awesome-advanced-persistent-threat-resource/graphs/contributors)!

### License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

[🔼 Back to top](#awesome-advanced-persistent-threat-apt-resources-)
