# Home Security Operations Centre (SOC) Lab
This project is a home SOC lab built using virtual machines to simulate real-world cyber security monitoring and incident detection. The lab includes an Ubuntu server running Splunk SIEM, a Windows machine generating logs, and a Kali Linux machine used to simulate attacks. The goal of this project is security monitoring, log analysis, and incident response.

Lab Architecture
The lab contains three virtual machines:
Ubuntu Server – Splunk SIEM
Windows 11 – Log generating machine
Kali Linux – Attacker machine
Logs from the Windows machine are forwarded to Splunk where security events are monitored and analysed.

## Lab Architecture

![SOC Lab Diagram](images/soc-lab-diagram.png)

## Tools Used
- UTM
- Ubuntu 24.04
- Windows 11
- Kali Linux
- Splunk SIEM
- Nmap
- Wireshark

## Incidents Simulated
- Failed login attempts
- Port scanning
- New user account creation
- Malware detection
