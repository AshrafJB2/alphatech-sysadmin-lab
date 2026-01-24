# Day 04 – Active Directory Structure: OUs, Users & Security Groups

## 🎯 Objective
Organize the Active Directory to simulate a real enterprise environment
by creating Organizational Units, security groups, and test users.

---

## 🖥️ Environment
- Domain Controller: AlphaTechDC01
- OS: Windows Server 2019
- Domain: alphatech.com
- AD Tool: Active Directory Users and Computers

---

## 1️⃣ Organizational Units (OUs)

Created the following OUs to represent company departments:

- **HR**
- **Finance**
- **IT**

![Active Directory OUs](../screenshots/day-04/ad-ous.png)

---

## 2️⃣ Security Groups And Users

Created security groups corresponding to each department:

- HR_SG
- Finance_SG
- IT_SG

Created users per OU:

| OU      | Users |
|---------|----------------------------|
| HR      | abderrahman.staili        |
| Finance | ikhlasse.amaiz            |
| IT      | achraf.jabbari, khawla.staili, youssef.staili |

- Assigned users to their respective security groups
- Verified user creation and group membership

![AD Users](../screenshots/day-04/security-groups-and-ad-users.png)

---

## 🔐 Why This Is Important
- OUs allow granular management of users and policies
- Security groups enable easy permission assignment
- User accounts simulate real enterprise workforce

---

## ✅ What I Learned
- Designing a structured Active Directory hierarchy
- Mapping users to departments
- Creating and managing security groups
- Understanding how OUs interact with Group Policies
