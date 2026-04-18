# 🔐 Enterprise Active Directory Implementation

## 📋 Project Overview
- **Client:** Ports Sacco Society Ltd
- **Duration:** 3 months (Feb 2025 - April 2025)
- **Role:** Lead IT Support Officer
- **Team Size:** 4 IT staff

## 🎯 Business Challenge
Ports Sacco had 71+ users across 6 locations with no centralized user management, leading to:
- 15+ hours weekly spent on manual user account management
- Security vulnerabilities from inconsistent permissions
- Slow login times (5+ minutes per user)
- No centralized password policy

## 🛠️ Solution Implemented

### Phase 1: Planning & Design
- Assessed existing infrastructure
- Designed AD hierarchy with OUs for each department
- Created naming conventions for users, groups, and computers

### Phase 2: Implementation
- Deployed Windows Server 2025 with AD DS role
- Configured DNS and DHCP integration
- Created 15+ security groups and 10+ distribution groups
- Implemented Group Policy Objects for:
  - Password complexity (12+ characters, expiration 30 days)
  - Folder redirection for Documents and Desktop
  - Software restriction policies
  - Windows update scheduling

### Phase 3: Migration
- Migrated 200+ user accounts from workgroup to domain
- Joined 150+ computers to domain
- Trained 50+ staff on new login procedures

### Phase 4: Documentation & Handover
- Created 20-page administrator guide
- Developed 5-page user quick reference guide
- Provided 2 weeks of hyper-care support

## 📊 Results & Achievements

| Metric | Before | After | Improvement |
|--------|--------|-------|-------------|
| Login time | 5-7 minutes | 30 seconds | 90% faster |
| Account creation time | 45 minutes | 5 minutes | 89% faster |
| Password reset time | 30 minutes | 2 minutes | 93% faster |
| Security incidents | 5/month | 0/month | 100% reduction |
| IT support tickets | 30/week | 12/week | 60% reduction |

## 💻 Technologies Used
- Windows Server 2025
- Active Directory Domain Services
- DNS Server
- DHCP Server
- Group Policy Management Console
- RSAT tools
