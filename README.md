# Secure Mission Training Environment Lab

This project documents the buildout of a secure cloud-based mission training environment in Microsoft Azure.

The lab demonstrates practical skills relevant to systems administration, network support, information assurance, and simulation/training environment support roles.

## Current Build Status

* Resource Group: RG-SecureMissionLab
* VNet: VNET-BlackScalpel-WE
* Region: West Europe
* Domain: blackscalpel.local
* Domain Controller: DC01
* DC01 Private IP: 10.0.2.10

## Network Design

| Subnet            |        CIDR | Purpose                       |
| ----------------- | ----------: | ----------------------------- |
| Admin-Subnet      | 10.0.1.0/24 | Admin access and management   |
| Server-Subnet     | 10.0.2.0/24 | Domain controller and servers |
| User-Subnet       | 10.0.3.0/24 | User/client systems           |
| Monitoring-Subnet | 10.0.4.0/24 | Logging, SIEM, and monitoring |

## What This Lab Demonstrates

* Azure virtual networking
* Subnet segmentation
* Windows Server administration
* Active Directory deployment
* DNS configuration
* User, group, and OU management
* Secure remote access planning
* Troubleshooting documentation

## Documentation

Documentation files will be added under the `/docs` folder as the lab progresses.
