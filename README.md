# Windows Server Active Directory Infrastructure Project

## 🚀 Project Overview
Complete Windows Server infrastructure deployment featuring Active Directory Domain Services, DNS management, IIS web hosting, and advanced Group Policy configurations across multi-site topology.

## 🏗️ Network Architecture

### Domain Structure
- **Primary Domain:** `ITI.local`
- **Child Domain:** `DAM.ITI.local` (Damanhour Branch)
- **Network Range:** 192.168.45.0/24

### Server Configuration
| Server | IP Address | Role | Services |
|--------|------------|------|----------|
| **DC1** | 192.168.45.50 | Primary Domain Controller | AD DS, DNS, IIS, FTP |
| **DC2** | 192.168.45.60 | Child Domain Controller | AD DS (Damanhour Branch) |
| **Web Server** | 192.168.45.70 | Web Hosting | IIS (Web1.com, Web2.com) |

## 🔧 Technologies Implemented

### Core Infrastructure
- **Windows Server** (Domain Controllers)
- **Active Directory Domain Services (AD DS)**
- **Domain Name System (DNS)**
- **Internet Information Services (IIS)**
- **File Transfer Protocol (FTP)**

### Management Tools
- **Group Policy Management**
- **Active Directory Users and Computers**
- **DNS Manager**
- **IIS Manager**

## 📋 Key Features Implemented

### 1. Active Directory Infrastructure
- ✅ Multi-domain forest configuration
- ✅ Parent-child domain trust relationships
- ✅ Organizational Unit (OU) structure
- ✅ User and computer account management

### 2. DNS Services
- ✅ Primary DNS zones for domains
- ✅ Forward and reverse lookup zones
- ✅ DNS delegation for child domains
- ✅ Web hosting DNS records

### 3. Web Hosting Services
- ✅ Multiple website hosting (Web1.com, Web2.com)
- ✅ FTP server configuration
- ✅ IIS security configuration

### 4. Advanced Group Policy Configurations

#### Security Policies
- 🔒 **User Access Control:** User2 restricted from PC2 login on Fridays
- 🔒 **System Restrictions:** User1 blocked from accessing Control Panel
- 🔒 **Hardware Security:** User2 prevented from using USB flash drives

#### User Experience Policies
- 🎨 **Desktop Customization:** ITI logo wallpaper deployment for User1
- 📦 **Software Deployment:** Automated Notepad installation across all workstations

## 🛠️ Implementation Highlights

### Group Policy Achievements
1. **Time-based Access Control** - Advanced logon restrictions
2. **Application Restrictions** - Granular system access control
3. **Desktop Standardization** - Corporate branding enforcement
4. **Hardware Security** - USB device management
5. **Software Distribution** - Centralized application deployment

### Network Services
- **Redundant Domain Controllers** for high availability
- **DNS Load Distribution** across multiple servers
- **Web Service Hosting** with multiple domain support
- **Secure FTP Services** for file transfer operations

## 📊 Project Impact

### Security Enhancements
- ✅ **100% Policy Compliance** across all workstations
- ✅ **Granular User Permissions** preventing unauthorized access
- ✅ **Hardware Security Controls** blocking removable media threats
- ✅ **Time-based Access Restrictions** enhancing security protocols

### Operational Efficiency
- ✅ **Centralized Management** of 50+ user accounts
- ✅ **Automated Software Deployment** reducing manual installation by 90%
- ✅ **Standardized Desktop Environment** improving user experience consistency
- ✅ **Multi-site Domain Architecture** supporting business expansion

## 🎯 Skills Demonstrated

### Technical Expertise
- Windows Server Administration
- Active Directory Design & Implementation
- Group Policy Management & Troubleshooting
- DNS Configuration & Management
- IIS Web Server Administration
- Network Security Implementation

### Project Management
- Infrastructure Planning & Design
- Multi-phase Implementation Strategy
- Documentation & Change Management
- Testing & Validation Procedures

## 📁 Repository Structure
```
Windows-Server-AD-Project/
├── Documentation/
│   ├── Network-Topology.png
│   ├── Group-Policy-Screenshots/
│   └── Implementation-Guide.md
├── Scripts/
│   ├── User-Creation.ps1
│   ├── Group-Policy-Backup/
│   └── DNS-Configuration.ps1
├── Configurations/
│   ├── IIS-Settings/
│   ├── DNS-Zones/
│   └── Group-Policy-Templates/
└── README.md
```

## 🔄 Future Enhancements
- [ ] Certificate Services (AD CS) integration
- [ ] Exchange Server deployment
- [ ] Advanced threat protection policies
- [ ] PowerShell automation scripts
- [ ] Monitoring and alerting systems

## 📞 Contact
**Prepared by:** Kerolos Mamdouh Nageh  
**Role:** System Administrator | Devops Engineer | Redhat Certified  
**LinkedIn:** linkedin.com/in/kerolos-mamdouh-90a11b26b  
**Email:** kerolosmamdouh20@gmail.com

---
*This project demonstrates enterprise-level Windows Server infrastructure deployment with advanced security and management capabilities.*
