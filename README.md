<!-- README.md – Lahat Fall -->
<!-- Version SOC avancée – MITRE × VERIS × Elastic × Incident-driven -->

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=lahat-fall&color=blue" alt="Profile views" />
</p>

<h1 align="center">Lahat Fall</h1>
<h3 align="center">
  Analyste SOC (Junior Avancé) · DFIR · Cyber Defense  
  <br>
  B.Sc. Informatique – Sécurité des Réseaux (en cours) @ UQAC  
</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/lahat-fall-569900300" target="_blank">LinkedIn</a>
</p>

---

## À propos

> *La cybersécurité ne se résume pas aux alertes, mais à la capacité de produire des décisions fiables.*

Analyste **SOC junior avancé**, orienté **surveillance, triage, investigation et qualification d’incidents**, avec une approche **incident-driven** et **data-driven**.

Je conçois, déploie et exploite des **environnements SOC open-source réalistes**
reposant sur **Wazuh, Elastic Stack, Suricata, Zeek et TheHive**, avec un focus sur :
- la **réduction des faux positifs**,
- la **priorisation des alertes à forte valeur**,
- la **structuration des incidents**,
- la **capitalisation de la connaissance SOC**.

Je maîtrise la chaîne complète de traitement des logs SOC :
**collecte (Beats)**, **transformation (Logstash)**, **indexation (Elasticsearch)**
et **exploitation opérationnelle (Kibana)**, avec une attention particulière
à la qualité des données et à la corrélation orientée incident.

---

## Approche SOC : MITRE ATT&CK × VERIS

J’utilise **MITRE ATT&CK** et **VERIS** de manière complémentaire afin de structurer
le travail SOC **de l’alerte technique jusqu’à l’incident métier**.

### MITRE ATT&CK — Couche détection & analyse
- Mapping des alertes SIEM / IDS vers des **TTP observables**
- Corrélation de multiples alertes autour d’une **même chaîne d’attaque**
- Support au triage, à la priorisation et à l’escalade SOC

MITRE est utilisé comme **outil d’analyse opérationnelle** pour comprendre
*comment* une attaque se déroule.

### VERIS — Couche incident & décision
- Qualification des **incidents réels** après investigation
- Modélisation selon :
  - **Acteur**
  - **Action**
  - **Actif**
  - **Impact**
- Distinction claire entre :
  - événement
  - alerte
  - activité suspecte
  - incident avéré

VERIS permet de traduire des signaux techniques en **incidents exploitables**
par le SOC et compréhensibles par le management.

---

## Cycle SOC : de l’alerte à la connaissance

Événement  
→ Alerte SIEM / IDS  
→ Triage Analyste SOC  
→ Mapping MITRE ATT&CK  
→ Corrélation multi-alertes  
→ Qualification de l’incident  
→ Modélisation VERIS  
→ Escalade / Reporting  
→ Amélioration continue du SOC

Cette approche permet au SOC de produire **de la connaissance**, et non
uniquement du volume d’alertes.

---

## Projets clés

| Projet | Focus SOC | Résultat |
|------|----------|----------|
| **SOC-Lab Entreprise (PFE)** | Détection, corrélation, qualification | Incidents classés MITRE + VERIS |
| **Wazuh SCA AI Analyst** | Enrichment & priorisation | ↓ ~60 % du temps d’analyse |
| **Forensic Memory Analysis** | Post-incident | Rapports DFIR structurés |
| **SuricataDashboard** | IDS tuning | Réduction du bruit |
| **Cloud Hardening & Monitoring** | Détection Cloud | Alertes exploitables |

### SOC-Lab Entreprise — détails
- Ingestion et normalisation des logs via **Elastic Stack**
- Corrélation des alertes via **MITRE ATT&CK**
- Reconstruction de chaînes d’attaque simulées
- Qualification des incidents selon **VERIS**
- Séparation claire : alertes techniques vs incidents métier
- Capitalisation pour amélioration continue du SOC

---

## Domaines de compétence

### SOC & Détection
- SIEM : **Wazuh, Elastic Stack (Beats, Logstash, Elasticsearch, Kibana), Splunk**
- Ingestion, parsing et normalisation de logs multi-sources
- IDS / NDR : Suricata, Zeek
- Corrélation d’événements et mapping MITRE ATT&CK
- Triage, priorisation, gestion de l’alert fatigue

### Modélisation Incident & Knowledge SOC
- VERIS : acteur, action, actif, impact
- Distinction événement / alerte / incident
- Reporting post-incident structuré
- Support à la décision SOC

### Forensic & Incident Response
- FTK Imager, Volatility, Autopsy
- Analyse mémoire, disque, journaux
- Support escalade DFIR

### Automatisation & Analyse SOC
- Python (playbooks SOC, enrichment, parsing logs)
- **Analyse de données SOC : Python, R**
- Statistiques descriptives appliquées aux alertes et incidents
- Bash, PowerShell
- CI/CD (GitHub Actions), Ansible (bases)

### Cloud & Hybride (niveau junior)
- Azure AD, Microsoft Sentinel
- AWS IAM, CloudTrail, audit S3
- Journalisation centralisée

---

## Stack SOC

`Wazuh` · `Elastic Stack (Beats, Logstash, Elasticsearch, Kibana)` ·  
`Suricata` · `Zeek` · `TheHive` · `Cortex` ·  
`MITRE ATT&CK` · `VERIS` ·  
`Python` · `R` · `Linux` · `pfSense` · `Git`

---

## Expérience

**Analyste SOC N1** — *Gendarmerie Nationale du Sénégal*  
*Janv. 2025 – Présent*  
*(Environnement opérationnel interne – périmètre non sensible)*  
- Surveillance et triage d’alertes SIEM  
- Réduction des faux positifs  
- Mapping MITRE et corrélation multi-alertes  
- Qualification des incidents selon VERIS  
- Documentation et escalade SOC

**Stagiaire Cybersécurité / SOC** — *Université du Québec à Chicoutimi (UQAC)*  
*Sept. 2024 – Déc. 2024*  
- Déploiement et exploitation d’un SOC open-source  
- Tuning IDS et règles de détection  
- Rédaction de procédures SOC

---

## Certifications & Formations SOC

- Microsoft SC-900 ✓  
- Cisco – Introduction to Network Automation  
- CompTIA Security+ — en cours  
- Microsoft SC-200 — en cours  
- Udemy — **Elastic Stack de A à Z** (2025)  
  *Ingestion, parsing, corrélation et visualisation de logs SOC*  
- Udemy — **Programmation R appliquée à l’analyse SOC** (2025)

🎯 **Trajectoire** : SOC Analyst → CySA+ → SOC L2 / DFIR

---

## Objectifs professionnels

- Analyste **SOC L1/L2**
- SOC d’entreprise, MSSP ou CERT
- Forte exposition à la détection réelle et à la donnée incident

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=lahat-fall&show_icons=true&theme=tokyonight" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=lahat-fall&layout=compact&theme=tokyonight" />
</p>

<p align="center"><em>Un SOC mature ne produit pas des alertes, il produit de la connaissance.</em></p>
