# Network Topology & Infrastructure

## 🌐 Network Configuration

### IP Address Allocation
| Server Role | Hostname | IP Address | Domain |
|-------------|----------|------------|---------|
| Primary DC | DC1 | 192.168.45.50 | ITI.local |
| Child DC | DC2 | 192.168.45.60 | DAM.ITI.local |
| Web Server | WEB1 | 192.168.45.70 | Web1.com / Web2.com |

## 🏗️ Domain Architecture

### Forest Structure

ITI.local (Root Domain)
└── DAM.ITI.local (Child Domain - Damanhour Branch)

### Services Distribution
- **DC1 (192.168.45.50)**
  - Primary Domain Controller
  - DNS Server (Primary Zones)
  - Global Catalog Server
  - IIS Web Server
  - FTP Server

- **DC2 (192.168.45.60)**
  - Child Domain Controller
  - DNS Server (Secondary Zones)
  - Branch Office Services

- **Web Server (192.168.45.70)**
  - IIS Hosting Platform
  - Web1.com Website
  - Web2.com Website

## 🔒 Security Zones
- **Domain Controllers:** High Security Zone
- **Web Servers:** DMZ Configuration
- **Client Workstations:** Standard Security Policies
