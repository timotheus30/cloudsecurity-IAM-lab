# Cloud-Based IAM Lab — Microsoft Entra ID

## Overview
This lab demonstrates cloud identity and access management using Microsoft Entra ID. The focus is on secure user lifecycle management, role-based access control (RBAC), auditing, and authentication enforcement without requiring premium features.

**Purpose:**  
- Build hands-on experience with cloud IAM  
- Enforce least-privilege access  
- Track administrative actions through audit logs  
- Test authentication using Microsoft Authenticator App  

---

## Tools & Resources
- Azure Free Account (with Entra ID)  
- Microsoft Entra ID (Free tier)  
- Microsoft Authenticator App (for MFA testing)  
- Azure Portal  

---

## Lab Steps

### 1. Create Users
- Created three test users:
  - `breakglassadmin@timothyfolaringmail.onmicrosoft.com`
  - `john@timothyfolaringmail.onmicrosoft.com`
  - `Mikey@timothyfolaringmail.onmicrosoft.com`
- Verified login with Microsoft Authenticator App for MFA simulation.

### 2. Create Security Groups
- `HR-Users`
- `IT-Admins`
- `Sales-Office`
- Assigned users to matching groups.

### 3. Create Resource Group
- Name: `CloudSec-IAM-RG`  
- Region: East US  
- Assigned RBAC roles to groups:
  - HR-Users → Reader  
  - IT-Admins → Contributor  
  - Sales-Office → Reader

### 4. Perform User Lifecycle Actions
- Added/removed users from groups  
- Disabled a test account

### 5. Audit & Logging
- Reviewed **audit logs** after actions
- Verified timestamps, actors, and targets
- Observed successful authentication via Microsoft Authenticator

---

## Screenshots
Include in `/screenshots` folder:
- Resource group overview
- Users and groups list
- RBAC assignments
- Audit log entries
- MFA authentication confirmation (blur sensitive info)

---

## Lessons Learned
- Enforced **least privilege access** using RBAC  
- Verified **audit logs** track admin actions  
- Practiced **MFA authentication testing**  
- Learned how to structure a cloud IAM lab for professional presentation

---

## Resume/LinkedIn Bullet
> Built a cloud-based IAM lab using Microsoft Entra ID, implementing user lifecycle management, RBAC, audit logging, and MFA authentication using Microsoft Authenticator App.
