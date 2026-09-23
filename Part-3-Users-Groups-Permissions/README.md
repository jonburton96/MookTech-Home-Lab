# Part 3 — Users, Groups & File Permissions

## Objective

Organize the MookTech domain by department and implement role-based access to shared network resources.

## Organizational Units

Created Organizational Units in Active Directory to organize users and resources by department.

The following OUs were created:

- `IT`
- `HR`
- `Employees`

## Security Groups

Created security groups to manage access based on organizational roles.

- `IT-Users`
- `HR-Users`
- `Student-Users`

Groups were configured as Global Security groups within Active Directory.

## User Management

Created domain users and assigned them to appropriate security groups.

User accounts were managed through Active Directory Users and Computers.

## Shared Folders

Created departmental shared folders on the Windows Server.

```text
C:\Shares\
├── HR
├── IT
└── Students
