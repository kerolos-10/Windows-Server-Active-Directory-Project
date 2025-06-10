# Group Policy Implementation

## 👤 User-Specific Policies

### User1 Restrictions
- ❌ **Control Panel Access:** Completely blocked
- 🖥️ **Desktop Wallpaper:** Enforced ITI corporate logo
- 📂 **System Access:** Limited to assigned applications only

### User2 Restrictions  
- 🗓️ **Time-Based Login:** Blocked from PC2 access on Fridays
- 🔒 **USB Security:** Flash memory/removable storage disabled
- 💻 **Workstation Access:** Restricted to specific computers

## 🏢 Organization-Wide Policies

### Software Deployment
- 📝 **Notepad Application:** Auto-install on all domain computers
- 🔄 **Update Management:** Centralized Windows Update configuration
- 🛡️ **Security Updates:** Automatic deployment and installation

### Desktop Standardization
- 🎨 **Corporate Branding:** ITI logo on all workstations
- 📋 **Start Menu:** Standardized application shortcuts
- 🔧 **System Settings:** Locked configuration management

## 🛠️ Implementation Method

### Policy Creation Process
1. **Group Policy Management Console (GPMC)**
2. **Organizational Unit (OU) targeting**
3. **Security group filtering**
4. **WMI filtering for specific conditions**
5. **Testing and gradual rollout**

### Enforcement Strategy
- **Immediate Effect:** Critical security policies
- **Scheduled Deployment:** Software installations
- **User Logon:** Desktop and application restrictions
- **Computer Startup:** System-wide configurations
