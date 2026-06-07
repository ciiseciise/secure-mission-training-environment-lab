# Active Directory Build

## Domain

- Domain Name: blackscalpel.local
- Domain Controller: DC01
- Server OS: Windows Server 2022

## Installed Roles

- Active Directory Domain Services
- DNS Server

## Organizational Units

Created OUs to separate users, computers, and groups.

- MissionLab-Users
- MissionLab-Computers
- MissionLab-Groups

![Active Directory OU Structure](../screenshots/active-directory/ad-ou-structure.png)

## Security Groups

Created security groups for role-based access control.

- Training-Users
- Server-Admins
- Helpdesk-Techs

![Active Directory Security Groups](../screenshots/active-directory/ad-security-groups.png)

## Test Users

Created test users for access-control validation.

- Training User One
- Helpdesk Tech One

![Active Directory Test Users](../screenshots/active-directory/ad-test-users.png)

## Group Membership Validation

Training User One was added to the Training-Users security group.

![Training User Membership](../screenshots/active-directory/ad-training-user-membership.png)

Helpdesk Tech One was added to the Helpdesk-Techs security group.

![Helpdesk User Membership](../screenshots/active-directory/ad-helpdesk-user-membership.png)

## What This Demonstrates

- Active Directory domain administration
- OU structure design
- User account creation
- Security group creation
- Group membership validation
- Basic role-based access control
