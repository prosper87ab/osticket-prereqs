# Active Directory Home Lab

## 📌 Overview
### Phase 4: Bi-Directional Governance & Cloud Writeback
* Deployed **Self-Service Password Reset (SSPR)** within Microsoft Entra ID utilizing Premium P2 tenant features.
* Engineered **Password Writeback** using Entra Connect Cloud Sync agents to intercept cloud-initiated password alterations and commit them down to on-premises domain security hives in real-time.
* Successfully validated zero-trust remote self-service lifecycle by resetting credentials via a cloud portal and immediately using them to unlock an on-premises domain-joined physical workstation (`PC01`).

## 🏗 Lab Architecture
- 1 Domain Controller (Windows Server)
- 1 Client Machine (Windows 10)
- Internal network

## ⚙️ Technologies Used
- Active Directory Domain Services
- Group Policy
- DNS
- Windows Server 2022

## 🔧 Key Implementations
- Installed and configured AD DS
- Promoted server to Domain Controller
- Created Organizational Units (OUs)
- Managed users and groups
- Joined client machine to domain
- Implemented Group Policies
- Simulated Joiner/Mover/Leaver lifecycle

## 🧪 IAM Scenarios Simulated
- User onboarding
- Role-based access control (RBAC)
- Account deprovisioning
- Access troubleshooting

## 📸 Screenshots
