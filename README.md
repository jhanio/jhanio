<h1 align="center">Jhanio Hernández</h1>

<p align="center">
  <b>IAM Analyst · Identity & Access Management · Microsoft Entra ID · Active Directory</b><br>
  Identity Security · Authentication · Authorization · Access Control · Enterprise IT
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Open%20to-Work-2ea44f?style=flat-square" alt="Open to Work"/>
  <img src="https://img.shields.io/badge/Open%20to-Remote%20Opportunities-0A66C2?style=flat-square" alt="Remote"/>
  <img src="https://img.shields.io/badge/Open%20to-Relocation-6f42c1?style=flat-square" alt="Relocation"/>
</p>

<p align="center">
  <a href="mailto:jhaniohernandez@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://www.linkedin.com/in/jhaniohernandez/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
</p>

---

## 👋 About Me

I am an **Identity & Access Management (IAM) professional** with an enterprise IT support background and hands-on experience with **user identities, accounts, permissions, authentication issues, access control, Active Directory, Microsoft 365, ITSM, and access-related incident management**.

My technical background goes beyond account administration. I build and analyse systems where **authentication, authorization, roles, APIs, databases, auditability, and security controls** must work together.

That combination gives me two perspectives on Identity Security:

**Operational:** resolving authentication and access incidents in enterprise environments.

**Technical:** understanding how applications enforce identity, roles, permissions, sessions, and access controls behind the interface.

I am currently deepening my specialization in **Microsoft Entra ID and Identity Security**, with a career path toward IAM Engineering, PAM, and Identity Security Architecture.

---

## 🔐 Identity & Access Management

**Identity Operations**

`Identity & Access Management (IAM)` · `User Account Management` · `Access Control` · `Authentication` · `Authorization` · `Permission Management`

**Microsoft Identity**

`Microsoft Entra ID` · `Active Directory` · `Microsoft 365`

**Identity Security**

`RBAC` · `MFA` · `Conditional Access` · `Identity Governance` · `PIM` · `SSO` · `Zero Trust`

> MFA, Conditional Access, Identity Governance, PIM, SSO, Zero Trust and PowerShell are areas of active professional development.

---

## 🛠️ Tools & Platforms

### Identity & Enterprise

`Microsoft Entra ID` · `Active Directory` · `Microsoft 365`

### ITSM & Operations

`ServiceNow` · `Jira` · `Incident Management` · `SLA` · `ITIL` · `L1 → L2/L3 Escalation`

### Security & Observability

![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square\&logo=splunk\&logoColor=white)

`Log Analysis` · `Troubleshooting` · `RCA` · `Technical Documentation`

### Engineering

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square\&logo=typescript\&logoColor=white)

`REST APIs` · `JWT` · `RBAC` · `RLS` · `Supabase` · `PostgreSQL` · `GitHub Actions`

---

# 🛡️ Identity & Security Engineering — Selected Work

My repositories are not presented only as software projects. They demonstrate how I approach **identity, authentication, authorization, access control, security boundaries, auditability, and system architecture**.

---

## 🔐 Horus — Authentication, RBAC & Row-Level Security

A particularly relevant project to my **IAM / Identity Security** path.

The system implements application-level identity and authorization controls using authenticated users, roles, database security policies, and server-side identity validation.

### Identity & Security concepts applied

`Authentication` · `Authorization` · `RBAC` · `Row-Level Security (RLS)` · `JWT-based Identity` · `Auditability` · `Least Privilege`

### Security engineering work

* Authentication and role-based authorization.
* User and role management.
* PostgreSQL/Supabase **Row-Level Security (RLS)**.
* Server-side identity validation using authenticated user context.
* Protection against user identity spoofing in database operations.
* Audit-oriented attribution of authenticated actions.
* Integration and regression testing for security controls.
* CI validation through GitHub Actions.

One security review identified that an authenticated request could potentially submit another user's identifier to a database operation.

The control was hardened so the operation derives identity from the **authenticated session (`auth.uid()`)** instead of trusting client-supplied identity.

That is the principle I want my IAM work to reflect:

> **Identity must be established by a trusted authority — never merely trusted because the client says who it is.**

**Relevant technologies**

`Supabase Auth` · `PostgreSQL` · `RLS` · `TypeScript` · `Next.js` · `GitHub Actions`

---

## 🧠 GynFem — Predictive Clinical Platform

Clinical decision-support application combining machine learning with protected application access.

The system integrates predictive services with authenticated application workflows and role-based interfaces.

### Identity & Access concepts

`Authentication` · `JWT` · `Protected APIs` · `Role-Based Access Control` · `Authorization`

Implemented application roles include:

`Doctor` · `Obstetrician` · `Administrator`

Clinical endpoints require authenticated access, while administrative functionality is restricted according to role.

### Engineering

`Python` · `FastAPI` · `Random Forest` · `REST API` · `JWT` · `RBAC` · `Automated Testing`

This project demonstrates my ability to understand Identity not as an isolated directory service, but as part of the complete application security architecture:

**User → Authentication → Token → Authorization → API → Protected Resource**

---

## 🏥 GynFem Platform — Secure Cloud Application Architecture

Web platform for clinical and administrative management built around a modern cloud architecture.

### Architecture & Engineering

`Next.js` · `TypeScript` · `Supabase` · `PostgreSQL` · `GitHub Actions` · `Vercel`

The repository includes structured technical documentation covering:

* Product requirements
* Application architecture
* Database design
* Environment configuration
* Development roadmap
* CI/CD workflows

The project provides practical exposure to the relationship between:

**Identity → Application → Database → Cloud → Deployment**

This architectural perspective is valuable in IAM because modern identities rarely exist in isolation — they provide controlled access to applications, APIs, data, and cloud resources.

---

## 🧪 Maternal Risk Prediction — ML Engineering

Predictive healthcare system using a **Random Forest** model exposed through an API for maternal-risk classification.

`Python` · `Scikit-learn` · `FastAPI` · `REST API` · `Machine Learning` · `Testing`

The project complements my Identity Security profile by demonstrating backend engineering, API integration, data processing, model deployment, and technical testing.

---

## 🔬 What These Projects Demonstrate

```text
Identity
   ↓
Authentication
   ↓
Authorization
   ↓
Roles & Permissions
   ↓
Application / API
   ↓
Protected Data
   ↓
Logging & Auditability
```

My goal is not simply to know where to click in an IAM console.

I want to understand **what happens to identity across the entire technology stack**.

---

## 📚 Current Identity Security Development

Currently strengthening practical knowledge in:

`Microsoft Entra ID Administration`

`Multi-Factor Authentication (MFA)`

`Conditional Access`

`Role-Based Access Control (RBAC)`

`Privileged Identity Management (PIM)`

`Identity Governance`

`Single Sign-On (SSO)`

`Zero Trust`

`PowerShell for Identity Automation`

---

## 🎓 Education

**Systems Engineering**
Universidad Peruana de Ciencias Aplicadas (UPC) · Expected 2026

**Computing & Information Technology**
CIBERTEC

---

## 🎯 Professional Direction

**Current Target**

`IAM Analyst` · `Identity & Access Management Analyst` · `Identity Security Analyst`

**Career Development**

`IAM Analyst → IAM Engineer → Senior IAM / PAM Engineer → Identity Security Architect`

---

<p align="center">
  <b>Identity is not just account administration — it is the control plane between users and digital resources.</b>
</p>

<p align="center">
  Open to remote opportunities and relocation.
</p>

<p align="center">
  <a href="mailto:jhaniohernandez@gmail.com">📧 Email</a> ·
  <a href="https://www.linkedin.com/in/jhaniohernandez/">💼 LinkedIn</a>
</p>
