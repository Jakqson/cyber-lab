## Day 1 
###### 1 Lab Overview
This lab environment is designed to simulate a real-world network for cybersecurity training and penetration testing practice.
![[ctbersec.png]]
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
![[Pasted image 20260330164510.png]]