---
title: Ankit's Endpoint Engineering Knowledge Map
markmap:
  colorFreezeLevel: 2
  initialExpandLevel: 2
  maxWidth: 280
---

# Ankit's Endpoint Engineering Knowledge Map

## 01 — Microsoft Intune
### Architecture & management
- Intune architecture
- Mobile Device Management (MDM)
- Mobile Application Management (MAM)
- Company Portal
### Enrollment & lifecycle
- Windows enrollment and Entra joined devices
- Device registration and enrollment profiles
- Device check-in and synchronization
- Retirement, wipe, reset, and offboarding
### Configuration & compliance
- **200+ Windows and macOS configuration profiles**
- Device configuration and security settings
- Compliance policies
- Device groups and policy assignment
### Applications & reporting
- Application management
- **150+ Win32 and Microsoft Store apps deployed through Company Portal**
- Deployment status and device reporting
- Enrollment and policy troubleshooting

## 02 — Windows
### Administration
- Windows 10 and Windows 11
- Device and local administration
- Configuration profiles
- Group Policy and registry settings
### Windows Autopilot
- Hardware hash and device registration
- Deployment profiles
- Out-of-box experience (OOBE)
- Enrollment Status Page (ESP)
- Application deployment during provisioning
- Company Portal and Store deployment considerations
- Autopilot device preparation concepts
### Security & support
- BitLocker encryption
- Windows Local Administrator Password Solution (LAPS)
- Local administrator management
- Windows security configuration
- Troubleshooting

## 03 — Microsoft Entra ID
### Identity, groups & devices
- User and identity administration
- Security groups and dynamic groups
- Device identity and join state
### Authentication
- Multifactor authentication (MFA)
- Passwordless authentication and passkeys
- Authentication methods and strengths
- Authentication security
### Conditional Access
- Users, groups, and target applications
- Conditions
  - Device platform and state
  - Locations and client apps
  - Risk-based controls: concepts
- Grant controls
  - MFA and authentication strength
  - Require compliant devices
  - Block access
- Session controls and device filters
- Report-only mode and pilot deployment
- Managed versus unmanaged devices
### Investigation
- Sign-in logs and audit logs
- Unusual sign-ins and session analysis
- Legacy authentication and ROPC analysis
- Session revocation and credential rotation

## 04 — Application Engineering
### Windows packaging
- Win32 and .intunewin
- MSI and MSIX
- Microsoft Store apps
- Offline and Company Portal deployment scenarios
### Deployment logic
- Install and uninstall commands
- Detection rules and scripts
- Requirements and return codes
- Dependencies and supersedence
- Assignment and deployment troubleshooting
### Cross-platform delivery
- macOS: PKG and DMG
- Mobile managed applications
- Installation, removal, and logging scripts
### Application packaging examples
- Docker Desktop, Node.js, and JDK
- Visual Studio, PyCharm, and Cursor
- STM32CubeMX and PulseView / Sigrok
- SourceTree, draw.io, and Company Portal

## 05 — Apple Management
### Enrollment
- Apple Business Manager (ABM)
- ABM integration with Intune
- Apple Push Notification service (APNs)
- Automated Device Enrollment (ADE)
### Platforms & configuration
- macOS, iOS, and iPadOS
- Configuration profiles and MobileConfig
- Apple Silicon versus Intel considerations
- Rosetta deployment checks
### Applications & scripts
- PKG and DMG deployment
- Adapt Microsoft/reference Bash and Zsh scripts
- Deploy scripts through Intune
- Maintain reusable scripts in GitHub
### Security & identity
- Microsoft Defender for Endpoint on macOS
- FileVault
- Platform SSO concepts

## 06 — Mobile Management
### Android
- Android Enterprise enrollment
- Managed Google Play integration
- Managed application deployment
### iOS & iPadOS
- Corporate and personally owned devices
- BYOD policy management
### MAM & app protection
- Corporate application data protection
- User and device assignments
- Inclusion and exclusion groups
- Guest and VIP assignment scenarios
- Managed application concepts

## 07 — Security
### Endpoint protection
- Intune endpoint security policies
- Microsoft Defender integration
- Microsoft Defender for Endpoint on macOS
- Firewall policies
- Security baselines
- Attack Surface Reduction concepts
### Device hardening
- BitLocker and FileVault
- Windows LAPS
- Local administrator controls
- Windows and macOS security configuration
### Identity & access
- Compliance and Conditional Access
- MFA, passwordless authentication, and passkeys
- Zero Trust concepts
### Security operations context
- Distinguish Intune management from third-party EDR/MDR
- Sophos MDR environment exposure

## 08 — Microsoft 365
### Collaboration & administration
- Exchange Online
- SharePoint Online
- OneDrive
- Microsoft Teams
- Microsoft 365 security administration
### Email security
- Mail flow and transport rules
- Anti-spoofing
- SPF, DKIM, and DMARC
- External mail restrictions
- Quarantine concepts

## 09 — PowerShell & Automation
### Endpoint workflows
- Application deployment and removal
- Detection and remediation scripts
- Device and security configuration
- Local administration
- Environment variable configuration
### Operational quality
- Structured logging
- Deployment-specific log files
- Troubleshooting and repeatable execution
- GitHub script maintenance
### Microsoft Graph
- Graph integration and automation concepts
- Advanced Graph automation: learning track

## 10 — Troubleshooting & Monitoring
### Scenarios
- Enrollment and MDM
- Windows Autopilot
- Application deployment
- Device compliance
- Intune Management Extension (IME)
- Identity and authentication
### Tools & evidence
- Intune admin center and Company Portal
- Event Viewer and PowerShell
- Registry, dsregcmd, and gpresult
- MDM and Autopilot diagnostics
- Enrollment and application logs
- Sign-in and audit logs
- Microsoft Graph
### Investigation method
- Symptom → Investigation → Evidence
- Root cause → Resolution → Prevention
- Monitoring and operational reporting

## 11 — Governance & Operations
### Access & organization
- Role-Based Access Control (RBAC)
- Naming conventions
- Group strategy
- Policy and application assignments
### Controlled rollout
- Pilot rings
- Change management
- Documentation and operational procedures
- Device lifecycle and offboarding

## 12 — Infrastructure & Hybrid Management
### Systems administration
- Windows Server
- Linux
- Infrastructure administration and IT support
### Legacy & hybrid management
- SCCM / Microsoft Configuration Manager
- Traditional Windows management
- Co-management concepts
- Group Policy to Intune migration
### Network & security
- Network and security concepts
- Connectivity troubleshooting
- Identity and endpoint integration

## 13 — Advanced / Learning
- Microsoft Graph API: advanced use
- Advanced automation
- GitHub Actions
- Azure Automation
- Infrastructure as Code (IaC)
- Power BI reporting
- Endpoint engineering at scale
- AI infrastructure

## 14 — Multi-Tenant Management
### Administration & separation
- Tenant administration
- Identity separation
- Security boundaries
### Device & policy operations
- Device management
- Policy management
- Group strategy
- Assignment management
### Delegation & governance
- RBAC
- Scope tags
- Reporting
- Change management
- Documentation

## Portfolio & Sources
### Selected public repositories
- [ADuser](https://github.com/AnkitKushwahaIT/ADuser)
  - PowerShell scripts for Active Directory users
- [linux-entra-sso](https://github.com/AnkitKushwahaIT/linux-entra-sso)
  - Fork of Siemens' Linux Entra SSO project
- [Intunewin_Create_Extract](https://github.com/AnkitKushwahaIT/Intunewin_Create_Extract)
  - Fork of Damien Van Robaeys' Intunewin tooling
### Profile & history
- [GitHub profile](https://github.com/AnkitKushwahaIT)
- [Knowledge map Markdown](https://github.com/AnkitKushwahaIT/AnkitKushwahaIT/blob/main/Ankit-GitHub-Profile-Markmap.md)
- [README history](https://github.com/AnkitKushwahaIT/AnkitKushwahaIT/commits/main/README.md)
