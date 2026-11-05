# Day 01: Active Directory Setup

**Date:** 05 Nov 2026
**Tools:** VMware Workstation, Windows Server 2022, Windows 10 Pro

## Goal
Build a domain environment, join a client to it, and practice basic user administration.

## Steps

### 1. Server Manager
![Server Manager](01-Active-Directory-Home-page.png)

### 2. Static IP configuration
Gave the server and the client static IPs on the same subnet. The client's DNS points to the server.
![Static IP](02-Active-Directory-Static-IP.png)

### 3. Install AD DS and promote to Domain Controller
Installed the AD DS role and DNS, then promoted the server to a domain controller (domain: System.in).
![AD DS Install](03-Active-Directory-Install.png)

### 4. Active Directory tools
![AD Tools](04-Active-Directory-Tools.png)

### 5. Active Directory Users and Computers
![Users and Computers](05-Active-Directory-Users-Computer.png)

### 6. Users
![Users](06-Active-Directory-Users.png)

### 7. Groups
![Groups](07-Active-Directory-Groups.png)

### 8. Organizational Units
Created a Company OU with HR, IT, Sales, Groups and Computers inside it.
![OUs](08-Active-Directory-Organizational-unit(OU).png)

### 9. Joined the Windows 10 client to the domain
Used `sysdm.cpl`, then Change, then Domain, and signed in with the admin account.

### 10. User administration
Logged in with a domain user, then practiced reset password, unlock, disable, enable and delete.

## What I learned
- How a client finds the domain through DNS
- How OUs organize users and computers
- How to manage the account lifecycle


