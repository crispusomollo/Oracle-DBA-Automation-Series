# 🧠 Oracle DBA Automation Series

[![Oracle](https://img.shields.io/badge/Oracle-DBA-red)](https://www.oracle.com/database/)
[![Python](https://img.shields.io/badge/Python-Automation-blue)](https://www.python.org/)
[![Shell](https://img.shields.io/badge/Shell-Scripting-green)](https://www.gnu.org/software/bash/)
[![Status](https://img.shields.io/badge/Portfolio-Production%20Grade-brightgreen)](#)

A curated portfolio of **production-oriented Oracle DBA automation projects** demonstrating how database administrators **monitor, diagnose, control, and optimize performance** using SQL, Python, and shell scripting.

---

## 🧭 How to Navigate This Portfolio

* Start with **Session & Lock Monitoring** to see real-time incident detection
* Move to the **Performance Dashboard** for historical trends and tuning insight
* Finish with **Resource Manager Automation** to see how performance issues are proactively controlled

Each repository is standalone, but together they tell a **complete DBA operational story**.

---

## 🎯 Purpose of This Series

In enterprise environments, DBAs are expected to:

* Respond quickly to performance incidents
* Diagnose issues under pressure
* Protect critical workloads
* Enforce governance and SLAs
* Automate repeatable operational tasks

This series showcases those capabilities through **practical, script-driven solutions**.

---

## 🧩 Series Philosophy

Each project in this series maps to a core DBA responsibility:

1. **Detect** – Identify what is happening
2. **Diagnose** – Understand why it is happening
3. **Control** – Prevent or limit impact
4. **Optimize** – Improve sustained performance
5. **Automate** – Make solutions repeatable and auditable

---

## 📦 Projects in the Series

### 🧪 0. Performance Monitoring Pipeline (End-to-End DBA Workflow)

[![Repo](https://img.shields.io/badge/GitHub-View%20Repo-black)](https://github.com/crispusomollo/Performance-Monitoring-Pipeline)

**Focus:** Unified Detection → Diagnosis → Verification

**What it covers:**

* End-to-end performance execution pipeline
* AWR snapshot capture
* SQL tuning checks
* Index health validation
* Session & lock inspection
* Resource Manager verification
* System health checks

**Skills demonstrated:**

* Orchestrated DBA workflows
* SQL*Plus automation
* Pipeline verification logic
* Structured operational logging

➡️ Acts as the **glue layer** that ties all other projects together into a single DBA execution flow.

---

### 🔍 1. Oracle Session & Lock Monitoring Automation

[![Repo](https://img.shields.io/badge/GitHub-View%20Repo-black)](https://github.com/crispusomollo/Oracle-Session-Locking-and-Monitoring)

**Focus:** Detection & Incident Diagnosis

**What it covers:**

* Active session monitoring
* Blocking and lock contention analysis
* Incident-friendly logging
* Scripted troubleshooting workflows

**Skills demonstrated:**

* Oracle dynamic performance views
* Lock analysis
* Python-based monitoring
* Operational logging

➡️ First-response tooling when users report performance issues.

---

### 📊 2. Oracle Performance Dashboard & Tuning Automation

[![Repo](https://img.shields.io/badge/GitHub-View%20Repo-black)](https://github.com/crispusomollo/Performance-Dashboard-Tuning-Automation)

**Focus:** Trend Analysis & Performance Optimization

**What it covers:**

* Automated performance data collection
* AWR-based insights
* Python analytics using pandas
* HTML dashboard generation

**Skills demonstrated:**

* Performance baselining
* Trend analysis
* SQL tuning workflows
* CI / cron-friendly automation

➡️ Moves from reactive troubleshooting to proactive performance management.

---

### 🔧 3. Oracle Resource Manager (CPU & I/O Management)

[![Repo](https://img.shields.io/badge/GitHub-View%20Repo-black)](https://github.com/crispusomollo/Oracle-Resource-Manager)

**Focus:** Control & Workload Governance

**What it covers:**

* Resource Manager plan creation
* CPU and I/O allocation control
* Consumer group management
* Enforcement of workload priorities

**Skills demonstrated:**

* Oracle Resource Manager
* Workload isolation
* Governance automation
* Production-safe enforcement

➡️ Prevents performance incidents before they occur.

---

## 🔗 How the Projects Fit Together

```text
User Performance Complaint
        │
        ▼
Session & Lock Monitoring
        │
        ▼
Performance Dashboard & Trends
        │
        ▼
Resource Manager Controls
        │
        ▼
Stable & Predictable Performance
```

This flow mirrors how **experienced DBAs operate in production environments**.

---

## 🧑‍💼 Target Roles

This portfolio is relevant for:

* Oracle Database Administrators (Junior to Senior)
* Performance & Tuning Engineers
* Production Support DBAs
* Infrastructure / Platform Engineers
* DevOps engineers supporting Oracle workloads

---

## 🛠️ Technologies Across the Series

* Oracle Database internals (V$ views, AWR, Resource Manager)
* SQL / PL/SQL
* Python (automation, parsing, analytics)
* Shell scripting
* Linux scheduling (cron)

---

## 📌 How to Use This Repository

* Use this repository as an **index** to explore each project
* Review individual READMEs for deep technical details
* Walk through scripts to understand DBA decision-making
* Use projects as discussion points in interviews or technical reviews

---

## 🚀 Future Roadmap

Planned additions to the series:

* Alerting & notifications (email / Slack)
* PDB-level resource management
* Centralized logging integration
* Advanced workload automation
* CI-driven validation pipelines

---

## 💡 Why This Series Matters

This series demonstrates:

* Practical Oracle DBA experience
* Incident-driven problem solving
* Performance governance skills
* Automation-first mindset
* Clear operational thinking

It reflects **how DBAs actually work** when systems are under pressure.

