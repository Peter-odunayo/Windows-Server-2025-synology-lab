# Hybrid Enterprise IT Lab

This project is a private lab environment built to simulate a hybrid enterprise IT infrastructure using Windows Server 2025, Microsoft 365, Intune, Synology NAS, Ubuntu Server, and Windows client devices.

## Project Goal

The goal of this lab is to build and document a real-world hybrid IT setup that demonstrates:

- Active Directory Domain Services
- Domain-joined clients
- Synology NAS integration with Active Directory
- Ubuntu server integration
- Windows client management
- Hybrid identity and cloud management concepts
- Microsoft 365 and Intune administration
- Networking, DNS, file sharing, and authentication

## Lab Environment

### Core Systems
- Windows Server 2025
- Synology NAS
- Ubuntu Server
- Windows 11 Client Devices
- Microsoft 365 Tenant
- Intune / Endpoint Management

### Planned Services
- Active Directory Domain Services
- DNS
- Domain Join
- Shared File Storage
- Group Policy
- Hybrid Identity
- Device Management
- VPN Simulation
- Centralized Authentication

## Project Progress

### Domain Controller Deployment
- Successfully promoted server to Domain Controller
- Created forest: `peterlab.local`
- DNS configured automatically
- Verified domain functionality

### Synology NAS Integration
- Successfully joined Synology NAS to Active Directory
- Verified DNS and domain communication
- Enabled domain-based authentication

## Next Steps
- Join Windows client machines to domain
- Connect Ubuntu server to environment
- Configure shared folders and permissions
- Test domain user authentication across systems
- Implement Group Policy
- Add Microsoft 365 / Intune hybrid management
- Simulate remote access or VPN scenario
- Document full network topology

## Skills Demonstrated
- Windows Server administration
- Active Directory deployment
- DNS configuration
- Synology NAS integration
- Hybrid infrastructure planning
- System administration
- Network and identity management

## Notes
This project is for learning, testing, and portfolio purposes. It is not tied to a production company environment.