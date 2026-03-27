# Access Control Configuration

## Objective
Implement role-based access control (RBAC) using Active Directory security groups and Synology NAS shared folders.

---

## Configuration

- Implemented role-based access control (RBAC) model
- Created department-based security groups (HR, IT, Finance) in Active Directory
- Assigned folder permissions on Synology NAS using AD groups
- Restricted access to departmental shared folders based on group membership

---

## Access Model

| Resource        | Access Group        |
|----------------|--------------------|
| \\NAS\HR       | PETERLAB\HR        |
| \\NAS\IT       | PETERLAB\IT        |
| \\NAS\Finance  | PETERLAB\Finance   |
| \\NAS\LabData | PETERLAB\Domain Users |

---

## Validation

- Verified users can only access authorized folders
- Confirmed access restrictions across departments
- Tested access using domain user accounts