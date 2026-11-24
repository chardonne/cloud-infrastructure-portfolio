
# Windows Server Administration Lab

## Project Overview

This project documents a hands-on Windows Server administration lab using a virtual machine.

The objective was to configure Active Directory Domain Services, organize domain resources, apply Group Policy settings, and perform user account administration using PowerShell.

## Environment

- Windows Server virtual machine
- Active Directory Domain Services
- Domain: lab.local
- Group Policy Management
- Windows PowerShell 5.1

## Technical Tasks Completed

### 1. Active Directory Domain Services
- Installed the AD DS role.
- Configured the server as a domain controller.
- Created the lab.local domain.

### 2. Organizational Units
Created organizational units to organize users and resources:
- Finance
- Human Resources
- Information Technology
- Sales

### 3. Group Policy Management
- Created and configured a Group Policy Object.
- Configured a removable storage access restriction.
- Enabled the policy to deny access to all removable storage classes.

### 4. PowerShell Administration

Practiced Active Directory administration commands for:

- Adding users to security groups.
- Resetting user passwords.
- Requiring password changes at next login.
- Unlocking user accounts.
- Disabling user accounts.

## Troubleshooting and Observations

During domain controller configuration, Windows Server displayed a DNS delegation warning because the authoritative parent zone could not be found.

The warning indicated that no action was required for this isolated lab environment.

The prerequisite check also identified the need for static IP configuration for reliable DNS operation.

## Skills Demonstrated

- Windows Server administration
- Active Directory
- Domain controller configuration
- Organizational Unit management
- Group Policy
- PowerShell
- User and group management
- Technical documentation
- Troubleshooting

## Project Status

Initial lab configuration completed.

Further testing and verification of Group Policy application will be documented in a future update.

## Evidence

Screenshots and a demonstration video will be added after sensitive information has been removed.
