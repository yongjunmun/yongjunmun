<div align="center">

<img src="https://raw.githubusercontent.com/yongjunmun/yongjunmun/main/assets/portrait-pixel.png" width="432" alt="Pixel-art cartoon of Yong Jun Mun standing on the coast shading his eyes from the sun">

# Yong Jun Mun

### I make automation easier to recover, verify, and trust.

Mechatronics Systems undergraduate working where equipment, controls, operations and software meet.<br>
Just finished a year as an Automation Engineer Intern in semiconductor manufacturing — AMHS, OHT/OHV, stocker and feeder systems.

[![Portfolio](https://img.shields.io/badge/Portfolio-yongjunmun.github.io-b45309?style=for-the-badge&labelColor=0f172a&logo=github&logoColor=white)](https://yongjunmun.github.io/YongJunMun_Resume/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-yong--jun--mun-334155?style=for-the-badge&labelColor=0f172a&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yong-jun-mun/)
[![Email](https://img.shields.io/badge/Email-junmun234%40gmail.com-334155?style=for-the-badge&labelColor=0f172a&logo=gmail&logoColor=white)](mailto:junmun234@gmail.com)
![Location](https://img.shields.io/badge/Based%20in-Singapore-334155?style=for-the-badge&labelColor=0f172a)

</div>

---

## Toolkit

![Python](https://img.shields.io/badge/Python-334155?style=flat-square&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-334155?style=flat-square&logo=numpy&logoColor=white)
![C/C++](https://img.shields.io/badge/C%2FC%2B%2B-334155?style=flat-square&logo=cplusplus&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-334155?style=flat-square&logo=powershell&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-334155?style=flat-square&logo=sqlite&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-334155?style=flat-square&logo=opencv&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-334155?style=flat-square&logo=tableau&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-334155?style=flat-square&logo=flask&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-334155?style=flat-square&logo=javascript&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-334155?style=flat-square&logo=githubactions&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-334155?style=flat-square&logo=playwright&logoColor=white)
![SOLIDWORKS](https://img.shields.io/badge/SOLIDWORKS-334155?style=flat-square&logo=dassaultsystemes&logoColor=white)

| | |
| :--- | :--- |
| **Automation systems** | AMHS · ASRS · AMR/AGV · OHT/OHV · digital packing line · stocker · feeder · handler systems |
| **Testing & reliability** | UAT · FMEA · RCA · exception testing · test-case design · preventive maintenance |
| **Control & embedded** | PID · LQR · MPC · state-space modelling · queueing theory · EKF · `solvePnP` · RTOS · Arduino · SPI / I²C / GPIO |
| **Software & data** | Python · NumPy · Flask · PowerShell · JavaScript · C/C++ · SQLite · REST APIs · Tableau · Excel · discrete-event simulation |
| **Operations tooling** | Fleet Manager · e-WareNavi · MCS · GT SoftGOT2000 · Task Scheduler |
| **Delivery** | Vendor coordination · OJTIs · operator training · technical handover |

---

## What I actually do

I turn unfamiliar production systems into repeatable recovery steps, defensible test evidence, and tools people can act on.

- **On the floor** — diagnose alarms, clear jams and recover AMR, ASRS, AMHS, OHT/OHV, stocker, strapping, packing and handler equipment with technicians and vendors.
- **Before go-live** — design and execute UAT and exception tests, prepare FMEA evidence, reproduce faults, and retest vendor fixes until they hold.
- **After go-live** — build the dashboards, alert workflows and OJTIs that keep a system supportable once the project team leaves.
- **Off the clock** — rebuild the same class of problem in software so the trade-offs become measurable: control laws, fleet queueing, vision pose estimation.

<div align="center">

![50+ UAT cases designed and run](https://img.shields.io/badge/50%2B-UAT%20cases%20designed%20and%20run-334155?style=for-the-badge&labelColor=b45309)
![7 live OHV reliability views](https://img.shields.io/badge/7-live%20OHV%20reliability%20views-334155?style=for-the-badge&labelColor=b45309)
![3 controlled equipment OJTIs](https://img.shields.io/badge/3-controlled%20equipment%20OJTIs-334155?style=for-the-badge&labelColor=b45309)
![36 Priority 1 items in alert workflow](https://img.shields.io/badge/36-Priority%201%20items%20in%20alert%20workflow-334155?style=for-the-badge&labelColor=b45309)

</div>

---

## Currently

- **BEng (Hons), Mechatronics Systems** — Singapore Institute of Technology, graduating Apr 2027
- **Automation Engineer Intern, completed** — Infineon Technologies Asia Pacific, Singapore · Sep 2025 – Aug 2026
- **Capstone in progress** — synchronized RGB + LiDAR capture into an indoor digital twin for NVIDIA Isaac Sim
- **Available for full-time roles from Apr 2027** — automation, controls, test, reliability and industrial software

---

## Selected work

Every number below comes from a test suite or a study that lives in the repository — none of it is estimated.

| Project | What it is | Measured result |
| :--- | :--- | :--- |
| **[PLC Vision Production Cell](https://github.com/yongjunmun/PLC-Vision-Production-Cell)** | Dependency-free digital commissioning simulator for a PLC-style conveyor inspection cell — state sequencing, stopped-state permissives, guarded recovery, motion-relative reject timing, SQLite traceability and a live browser HMI. | 96 tests · 8/8 interlocks enforced · deterministic PASS / FAIL / UNCERTAIN |
| **[AMHS Fleet Simulator](https://github.com/yongjunmun/AMHS-Fleet-Simulator)** | Discrete-event model of a semiconductor-fab OHT loop, built to find the point where adding vehicles stops helping. | Cycle time bottoms out at **123.1 s with 13 vehicles**, then rises **34.1%** by 21 while throughput stays flat |
| **[Inverted Pendulum Control Lab](https://github.com/yongjunmun/Inverted-Pendulum)** | Cascaded PID, LQR, MPC and energy swing-up benchmarked on one plant, one actuator limit and one cost function. Both Riccati solvers and the constrained MPC solver are written from scratch in NumPy. | Across 169 mismatched plants: **LQR/MPC held 84.6%** vs **PID 55.6%** |
| **[ArUco AMR Visual Docking](https://github.com/yongjunmun/ArUco-AMR-Docking)** | Ground-truthed pose-estimation study and closed-loop visual docking for a differential-drive AMR. | Apparent-width estimator reached **99.8% range error** at 60° marker yaw; `solvePnP` stayed within **0.42%** and docked at **3.9 cm** |
| **[Limit Order Book & Matching Engine](https://github.com/yongjunmun/Limit-Order-Book-Engine)** | Limit order book, price-time-priority matching engine and NASDAQ ITCH 5.0 decoder written from scratch in header-only C++23, no dependencies. Direct-indexed price array with a two-level bitset summary, intrusive FIFO queues and a lock-free SPSC handoff. | Cancel is depth-independent — **142 ns with 100k orders on one level** vs 198 ns random · 80 cases / **873,869 assertions** · worst-case add **148× better** than a `std::map` baseline |
| **[Systematic Trading System](https://github.com/yongjunmun/Systematic-Trading-System)** | Event-driven research system — no-lookahead backtesting, shared R-multiple exits, volatility-targeted sizing, walk-forward checks and Deflated Sharpe analysis. | 259 tests · paper trading only, engineering practice rather than a profitability claim |
| **[E-Commerce Website](https://github.com/yongjunmun/E-Commerce-Website)** | Flask marketplace where independent sellers manage products and the platform separates seller takings from its 10% commission. Product options, image uploads, FTS5 search, guest checkout, owner dashboard. | 222 tests · accessible server-rendered UI |

<details>
<summary><b>Everything else I keep public</b></summary>

<br>

| Project | What it is |
| :--- | :--- |
| [SkyCast Weather Platform](https://github.com/yongjunmun/Weather_Website) | Flask progressive web app that scores the best outdoor window in the next 24 h and explains every penalty behind the score. Playwright, accessibility, visual and Lighthouse budget tests run on every push. |
| [Job Apply Assistant](https://github.com/yongjunmun/Job_Application) | Local-first job search and application tracker — extracts skills from PDF and DOCX resumes, flags agency bulk postings and ghost jobs, caches searches in SQLite. |
| [Multi-Provider AI Chrome Assistant](https://github.com/yongjunmun/Chrome-AI-Assistant) | Manifest V3 side-panel extension that reads the active page and answers questions about it across eight AI providers, with local API-key handling. |
| [Maintenance Issue Tracking Bot](https://github.com/yongjunmun/Whatsapp-To-Excel-Bot) | Converts informal WhatsApp machine-issue messages into structured Excel records. Feedback-driven filtering learns from reviewed false captures. Sanitised template with example data. |
| [Humanoid Digital Twin Pipeline](https://github.com/yongjunmun/Capstone-Humanoid-Digital-Twinning-Project) | Capstone software workstream. Currently defines the data contract, validation gates and pipeline automation — no reconstruction results claimed yet. |
| [Automation & Mechatronics Portfolio](https://github.com/yongjunmun/YongJunMun_Resume) | The no-build GitHub Pages site linked at the top. Semantic HTML, layered CSS, vanilla JavaScript, reduced-motion support and measured WCAG contrast. |

Production work that cannot be published — seven live Tableau OHV alarm and uptime views against a 99% target, an Excel/PowerShell restock workflow with Outlook alerts, and three controlled 12-hour OJTIs — is described on the [portfolio site](https://yongjunmun.github.io/YongJunMun_Resume/).

</details>

---

## Foundation

**BEng (Hons), Mechatronics Systems** — Singapore Institute of Technology · expected Apr 2027<br>
**Diploma, Mechatronics and Robotics Engineering** — Singapore Polytechnic · Apr 2021

Certified SOLIDWORKS CAD Design Associate (2025) · Google Project Management Professional Certificate (2025) · Cisco Certified Network Associate (2022) · bizSAFE Level 2 (2020) · ITE Director's List

---

<div align="center">

### Let's build systems that fail clearly and recover safely.

[**Portfolio**](https://yongjunmun.github.io/YongJunMun_Resume/) · [**LinkedIn**](https://www.linkedin.com/in/yong-jun-mun/) · [**Email**](mailto:junmun234@gmail.com)

</div>
