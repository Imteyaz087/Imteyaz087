# Hi, I'm Imteyaz Ahmad 泰伊穆 👋

### Semiconductor Systems Integration Engineer · 半導體系統整合工程師

Systems integration engineer in Kaohsiung, Taiwan — manufacturing software, and the
infrastructure underneath it.

My semiconductor work was at **Gether Technology (Oct 2022 – Feb 2023)**: SECS/GEM equipment-to-host
data pipelines into MES/EAP for semiconductor and IC-packaging (OSAT) customers, MES/ERP
modules in C#/.NET over SQL Server and Oracle, and root-cause analysis of tool
communication failures alongside cleanroom operators and equipment vendors. Before that,
three years running Azure and Windows Server infrastructure at 99.9% availability for
200+ users, and Bloomberg Terminal data operations at Wipro.

Seven-plus years in engineering roles across Taiwan and India. Taiwan APRC (permanent
resident) · MSc Engineering, NKNU · English (full professional) and Mandarin (conversational, NSYSU certificate).

---

### ⚡ What I work on

* **Equipment integration** — SECS/GEM ↔ MES/EAP interfaces, equipment telemetry, tool-comms root-cause analysis, automated yield/OEE reporting.
* **Manufacturing software** — MES, ERP and CRM modules in C#/.NET and Python: maintenance scheduling, spare-parts inventory, service-ticket tracking.
* **Infrastructure** — Azure, Windows Server, Active Directory, Cisco networking and VPN; keeping factory IT and OT systems online.

### 🛠️ Technical toolbox

| Category | Technologies |
| :--- | :--- |
| **Languages** | Python · C# / .NET · TypeScript · SQL · PowerShell |
| **Manufacturing** | SECS/GEM · MES / EAP · CIM · equipment-to-host integration |
| **Data** | SQL Server · Oracle |
| **Platform** | Azure · Windows Server · Docker · REST APIs |

---

### 🚀 Public code

Most of my work lives in private repositories. This one is public and runs end-to-end
from a clean checkout:

#### [booking-ranker](https://github.com/Imteyaz087/booking-ranker) — learning-to-rank, NumPy only

A complete ML loop in about 200 lines with no frameworks: data → features → train →
offline evaluation against a baseline → REST serving → Docker. On **simulated** booking
sessions (900 training, 300 held out, split by session so no user leaks across the
split), the learned ranker reaches **NDCG@10 0.739** and **Recall@5 0.943** against a
popularity baseline at 0.133. Seeded and deterministic, so `python recsys.py` reproduces
those numbers exactly, and every learned weight is interpretable.

---

### 🔬 Independent engineering practice · 2024.11 – present

Self-directed projects between roles, mostly in private repositories:

* Designed and built a cross-platform fitness app in React, TypeScript and Firebase — five locales and a ~7,000-test automated CI suite. App Store submission in progress.
* Run a local on-device LLM environment on Apple Silicon: model serving, quantisation, and throughput and memory tuning, plus the tooling around it.

---

### 📬 Contact

* **LinkedIn:** [linkedin.com/in/imteyazahmad](https://linkedin.com/in/imteyazahmad)
* **Email:** [imteyaz087@gmail.com](mailto:imteyaz087@gmail.com)
* **Based in:** Kaohsiung, Taiwan 🇹🇼 — Taiwan APRC, no work permit or sponsorship required
