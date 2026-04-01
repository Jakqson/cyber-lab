## Day 1 
###### 1 Lab Overview
This lab environment is designed to simulate a real-world network for cybersecurity training and penetration testing practice.
<img width="913" height="457" alt="ctbersec" src="https://github.com/user-attachments/assets/c988c510-fff0-4817-99c4-bd16885b1639" />

###### Virtual Machines Used:

**Kali Linux**
  - Role: Attacker machine
  - Purpose: Used for scanning, enumeration, and exploitation

**Metasploitable2**
  - Role: Vulnerable target
  - Purpose: Intentionally insecure machine for practicing attacks

**Windows Server 2019**
  - Role: Domain Controller / Server
  - Purpose: Simulates enterprise environment 
**Windows 10**
  - Role: Client machine
  - Purpose: Represents a normal user workstation in a network
###### 2. Network Setup

This lab uses two network adapters: NAT and Host-only. Each serves a different purpose.

###### NAT (Network Address Translation)
- Provides internet access to virtual machines
- Allows downloading tools, updates, and packages
- Connects VMs to the external network through the host machine
NAT is not used for attacks to avoid interacting with external systems.
###### Host-only Network
- Creates an isolated internal network between virtual machines
- No internet access
- Only VMs and the host can communicate
<img width="697" height="73" alt="image" src="https://github.com/user-attachments/assets/4171962e-fafa-4c6f-81ba-70776a822e33" />

## Day 2
###### OSI and TCP/IP model
**OSI Model**
 - Application Layer: User interaction(Fake website)
   Attacks: DNS Spoofing, Phishing and SQL ejection
 - Presentation Layer: Encryption and formatting(ssl and tsl)
   Attacks: SSL stripping and weak encryption exploitation
 - Session Layer: Manage session(logins)
   Attack: Hijack session
 - Transport Layer: Control Delivery(TCP/UDP)
   Attack: DoS, SYN Scan
 - Network Layer: Address IP
   Attack: IP Spoofing
 - Data Link Layer: Mac Address
   Atack: ARP Spoofing
 - Physical Layer: Cables
   Attack: Hardware tampring, packet sniffing

<img width="329" height="416" alt="image" src="https://github.com/user-attachments/assets/0e8f8d7d-4345-4070-a4ee-d8d75c87cc81" />

**OSI - TCP/IP Mapping**
Application Layer - Application
Presentation Layer - Application
Session Layer - Application
Transport Layer - Transport
Network Layer - Internet
Data Link Layer - Network Access
Physical Layer - Network Access

