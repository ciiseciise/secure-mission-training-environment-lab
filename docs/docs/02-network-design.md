
# Secure Mission Training Environment Lab

This project documents the buildout of a secure cloud-based training network in Microsoft Azure.

The lab is designed to demonstrate skills relevant to cleared IT, systems administration, network support, information assurance, and simulation/training environment support roles.

## Current Build Status

- Resource Group: RG-SecureMissionLab
- VNet: VNET-BlackScalpel-WE
- Region: West Europe
- Domain: blackscalpel.local
- Domain Controller: DC01
- DC01 Private IP: 10.0.2.10

## Subnet Design

| Subnet | CIDR | Purpose |
|---|---:|---|
| Admin-Subnet | 10.0.1.0/24 | Administration access |
| Server-Subnet | 10.0.2.0/24 | Domain controller and servers |
| User-Subnet | 10.0.3.0/24 | Client systems |
| Monitoring-Subnet | 10.0.4.0/24 | SIEM/logging tools |

## What This Lab Demonstrates

- Azure virtual networking
- Subnet segmentation
- Windows Server administration
- Active Directory deployment
- DNS configuration
- User, group, and OU management
- Secure access planning
- Troubleshooting documentation

## Documentation

- [Lab Overview](docs/01-lab-overview.md)
- [Network Design](docs/02-network-design.md)
- [Active Directory Build](docs/03-active-directory-build.md)
- [Security Controls](docs/04-security-controls.md)
- [Monitoring and Logging](docs/05-monitoring-and-logging.md)
- [Troubleshooting Tickets](docs/06-troubleshooting-tickets.md)
- [Lessons Learned](docs/07-lessons-learned.md)
