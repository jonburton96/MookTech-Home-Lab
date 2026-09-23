# Part 2 — Active Directory

## Objective

Deploy a Windows Server domain environment and connect Windows 11 clients to the Active Directory domain.

## Domain Controller

Configured Windows Server as the domain controller for the MookTech lab.

- Active Directory Domain Services installed
- DNS configured
- Domain created: `home.lab`
- Server IP: `192.168.10.3`

## Active Directory

Created the `home.lab` Active Directory domain and configured domain authentication.

Domain users were created through Active Directory Users and Computers.

## Domain-Joined Clients

Both Windows 11 Enterprise evaluation clients were successfully joined to the `home.lab` domain.

| Device | IP Address | Domain Status |
|---|---|---|
| Windows 11 Client 1 | `192.168.10.1` | Domain Joined |
| Windows 11 Client 2 | `192.168.10.2` | Domain Joined |

## DNS

Configured the Windows Server as the DNS server for the lab.

Client DNS configuration points to:

`192.168.10.3`

This allows the clients to locate and communicate with the `home.lab` domain.

## Domain Authentication

Verified that domain credentials could be used to authenticate to the Windows environment.

## Troubleshooting

Encountered issues with Windows 11 Home not supporting Active Directory domain joining. The clients were replaced with Windows 11 Enterprise evaluation installations to support domain integration.

Additional troubleshooting involved DNS resolution, domain credentials, and network connectivity.

## Screenshots

### Active Directory Users and Computers

![Active Directory Users and Computers](./Part-2-Active-Directory/screenshots/active-directory.png)

### Domain Users

![Domain Users](./Part-2-Active-Directory/screenshots/domain-users.png)

### DNS Manager

![DNS Manager](./Part-2-Active-Directory/screenshots/dns-manager.png)

### Domain-Joined Client

![Domain Joined Client](./Part-2-Active-Directory/screenshots/domain-joined-client.png)

### Domain Login

![Domain Login](./Part-2-Active-Directory/screenshots/domain-login.png)

## What I Learned

- Active Directory Domain Services
- Domain controllers
- DNS
- Domain authentication
- Active Directory Users and Computers
- Domain joining
- Windows Server administration
- DNS and network troubleshooting
