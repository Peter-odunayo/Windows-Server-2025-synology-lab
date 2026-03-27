# Network Configuration

## Initial Setup

- Configured network for Domain Controller (192.168.1.4)
- Set DNS to Domain Controller for all systems

---

## Network Issue Resolved

- Identified network mismatch between NAS (192.168.144.x) and Domain Controller (192.168.1.x)
- Reconfigured NAS network adapter from NAT to Bridged mode
- Assigned NAS IP within same subnet (192.168.1.x)
- Ensured all systems operate within the same network for proper domain communication