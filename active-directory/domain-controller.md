# Active Directory Domain Setup

## Objective
Deploy Active Directory Domain Services on Windows Server 2025 and use it as the identity core for the lab.

## Planned Tasks
- Assign static IP address
- Rename server to DC01
- Install AD DS and DNS roles
- Promote server to Domain Controller
- Create lab domain
- Join Windows 11 client to domain

# Active Directory Domain Setup

## Objective
Deploy Active Directory Domain Services and configure a domain controller.

---

## Network Configuration

- IP Address: 192.168.1.4
- Subnet Mask: 255.255.255.0
- Gateway: 192.168.1.254
- DNS Server: 192.168.1.4

---

## Domain Controller Deployment

- Successfully promoted server to Domain Controller
- Created forest: peterlab.local
- DNS configured automatically
- Verified domain functionality (PETERLAB domain active)

---

## Validation

- Logged in as: PETERLAB\Administrator
- Verified domain using:
  - `whoami`
  - `echo %userdomain%`