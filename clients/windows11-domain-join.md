# Windows Client Domain Join

## Objective
Join Windows 11 clients to Active Directory domain.

---

## Configuration

- Configured DNS to Domain Controller (192.168.1.4)
- Joined devices to domain: peterlab.local
- Authenticated using domain credentials

---

## Validation

- Successfully logged in using domain user account
- Verified Group Policy application
- Confirmed automatic NAS drive mapping

---

## Domain Authentication Verification

- Verified domain login using Active Directory user accounts
- Confirmed user context using `whoami`
- Validated Group Policy application and drive mapping
- Ensured role-based access to network resources