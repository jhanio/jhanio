<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=20&pause=1000&color=FF0000&center=true&vCenter=true&width=750&lines=Something+is+watching+your+network...;Every+packet+tells+a+story.;I+read+them+all.;Jhanio+Hernandez+%7C+SOC+Analyst+%26+Security+Engineer" alt="Typing SVG" />
</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/jhaniohernandez/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:jhaniohernandez@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <img src="https://komarev.com/ghpvc/?username=jhanio&style=for-the-badge&color=red&label=PROFILE+VIEWS"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/SOC%20Analyst-N1-red?style=flat-square"/>
  <img src="https://img.shields.io/badge/Oracle%20Cloud-Security-orange?style=flat-square&logo=oracle"/>
  <img src="https://img.shields.io/badge/CompTIA-Security%2B%20In%20Progress-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/English-Professional-green?style=flat-square"/>
</p>

---

<p align="center">
  <b>⚠️ You've just accessed a monitored profile. Every visit is logged. ⚠️</b>
</p>

---

## 🕵️ Who is behind this terminal?

There are engineers who build systems.  
And there are engineers who **secure** them.

I've done both.

2+ years on the front line — triaging incidents, enforcing access controls, escalating threats  
for **Atos / McDonald's USA** — in English, under SLA, at enterprise scale.

Now I'm going deeper into the threat layer:  
**SOC operations · Log analysis · Incident response · Cloud security.**

> *"I've seen what happens when a system fails at 2AM.*  
> *I want to be the one who catches it at 1:59."*

---

## 🛡️ Security Stack

```
[ SIEM & Monitoring ]   Splunk · Elastic Stack · Microsoft Sentinel
[ Incident Response ]   Triage · Escalation matrix · Post-incident review · ITSM
[ Network Security ]    TCP/IP · OSI Model · Firewalls · IDS/IPS · DNS
[ Cloud Security ]      Oracle Cloud ✅ · AWS IAM · Access Control · Secrets Mgmt
[ Endpoint ]            EDR concepts · Windows/Linux hardening · Credential mgmt
[ Scripting ]           Python · PowerShell · Bash · FastAPI
[ Frameworks ]          NIST · ISO 27001 concepts · ITSM/SLA · OWASP basics
[ AI + Security ]       LLM integration · Automated threat workflows · Prompt engineering
```

---

## 🏆 Certifications

| Status | Certification | Issuer |
|--------|--------------|--------|
| ✅ Active | Oracle Cloud Infrastructure Security | Oracle |
| ✅ Active | DevOps Foundations | Microsoft |
| ✅ Active | SAP ERP | SAP |
| ✅ Active | Agile Methodologies | — |
| 🔄 In progress | **CompTIA Security+** | CompTIA |

---

## 💼 Operational Experience

### 🔴 Helpdesk Analyst N1 — Teleperformance Perú
**Project: Atos × McDonald's USA · Feb 2024 – Mar 2026**

> Atos is a Top 10 global IT company with a dedicated Cybersecurity division.  
> I operated inside their enterprise support chain — English-only, zero margin for error.

- Incident triage, diagnosis and resolution for US corporate users across hundreds of locations
- Full ticket lifecycle management following strict ITSM protocols (open → escalate → close)
- Escalation to N2/N3 following security escalation matrix with full documentation
- Access resets and credential management under corporate security policies
- SLA compliance in 24/7 high-volume international operation
- Knowledge base documentation for recurring security incidents

**Translated to SOC language:**

| Helpdesk function | SOC equivalent |
|---|---|
| Incident triage | Alert triage and classification |
| Escalation matrix | SOC escalation to Tier 2/3 |
| Credential management | IAM and access control enforcement |
| SLA compliance | MTTR and incident response KPIs |
| KB documentation | Playbook and runbook creation |

*The environment was helpdesk. The discipline is SOC.*

---

## 🚨 Security-Focused Projects

### 🤖 GYNFEM — AI-Powered Clinic Automation *(Production)*
> Real patients. Real data. Real security requirements. Deployed and running.

WhatsApp bot + AI scheduling + electronic clinical records for a gynecological clinic in Peru.

`Python · FastAPI · Google Calendar API · Gemini AI · Google Apps Script · WSL2`

**Security design decisions:**
- Role-based access: receptionist / doctor / admin — separate permissions per module
- Patient data isolation — each record scoped to authenticated session
- Automated audit trail for all appointment modifications
- No PII exposed in API responses — stripped before bot output
- Webhook validation for incoming WhatsApp events

---

### 💬 INTRIGA — Attention Monetization Platform *(Architecture phase)*
> *"Your attention has value. Charge for it."*

Mobile + web platform enabling creators, artists and professionals to monetize  
direct interactions — pay-per-message, video calls, GPS radar, virtual gifts.

`React Native · Expo · Next.js · FastAPI · PostgreSQL · Redis · Stripe · Culqi · AWS`

**Security architecture highlights:**
- GPS coordinates obfuscated with ±200m noise — exact location never exposed to any user
- 5-tier identity verification system (Artist / Influencer / Entrepreneur / Verified / Basic)
- Per-field privacy controls — granular visibility per audience segment
- Payment fraud detection layer integrated with Stripe + Culqi (Peru)
- Block system: blocked users disappear from GPS radar and all search results
- Invisible mode: user active but undetectable on radar
- Rate limiting on all contact endpoints to prevent spam and abuse

*Status: PRD + TDD + Architecture complete · Development starting Q2 2026*

---

### ⚓ PORTIFY — Port Logistics Platform *(In development)*
Digital platform for port appointment management and cargo traceability — LATAM scale.

`Java · Spring Boot · PostgreSQL · Docker · Kubernetes`

**Security layer:** Role-based access for terminal operators, truckers and customs agents.  
Audit logs on all cargo state changes. JWT authentication with refresh token rotation.

---

### 🧬 ML HIGH-RISK PREGNANCY PREDICTOR *(In development)*
Predictive system for early detection of high-risk pregnancies in rural Peru.

`Python · Scikit-learn · Pandas · Matplotlib`

**Data security:** De-identified training dataset · No PII in model pipeline.

---

## 🤖 AI as a Security Tool

I don't just use AI — I integrate it into real production systems with security in mind.

| Tool | How I apply it |
|------|----------------|
| Claude (Anthropic) | Architecture review, threat modeling, automated security agents |
| Gemini API | NLP pipelines with input validation and output sanitization |
| Prompt Engineering | Designing tamper-resistant prompts for production bots |
| FastAPI + LLMs | Building secure API wrappers around AI models |

---

## 📡 Current config

```bash
$ cat /etc/target_roles.conf

TARGET_ROLE    = "SOC Analyst N1"
LOCATION       = "Lima, Peru | Remote LATAM"
ENGLISH_LEVEL  = "Professional — 2yr enterprise ops (Atos / McD USA)"
CLEARANCE      = "Available immediately"
STATUS         = "Operational"
```

---

## 🌍 The arc

```
FROM:  Helpdesk N1 · Atos / McDonald's USA · 2yr · EN
NOW:   Systems Engineering UPC · Técnico Cibertec · Oracle Cloud Security ✅
NEXT:  CompTIA Security+ 🔄
TO:    Cloud Security Engineer 🎯
```

---

<p align="center">
  <i>"The quietest systems are not always the safest ones."</i>
  <br/><br/>
  <b>Open to: SOC Analyst N1 · Security Ope
