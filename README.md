<div align="center">

# Alessandro Reyes

### Mechatronics engineer building AI that survives contact with real hardware.

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=2800&pause=1200&color=2540C0&center=true&vCenter=true&width=640&lines=Edge+AI+%2B+Robotics+%2B+Control+Systems;A+model+with+perfect+AUC+failed+on+real+silicon.+I+found+out+why.;1st+place%2C+OQI+Quantum+Computing+Hackathon+LATAM+2026;2%C3%97+IEEE+author+%E2%80%94+CASE+2026+%2B+BDAI+2026)](https://alesso-24.github.io/portfolio/)

[![Portfolio](https://img.shields.io/badge/Portfolio-alesso--24.github.io-2540C0?style=for-the-badge&logo=vercel&logoColor=white)](https://alesso-24.github.io/portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Alessandro_Reyes-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alessandro-reyes-mtz/)
[![Email](https://img.shields.io/badge/Email-jordi.reyes.martinez-EA6A2E?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jordi.reyes.martinez@gmail.com)

📍 Puebla, México · Mechatronics Engineering @ Universidad Iberoamericana Puebla · Open to Summer 2026 internships

</div>

<br>

## About

I build machine learning systems that have to survive contact with real, physical hardware, not just a clean dataset or a simulator. My published research exists because I went looking for where the theory breaks: a model with a "perfect" software score that silently failed the moment it ran on actual silicon. That gap between simulation and hardware is where I do my best work.

- 🔭 Currently building embedded/edge-AI systems at the intersection of control theory, ML, and firmware
- 🧪 Two IEEE conference papers, both hardware-validated on real ESP32 silicon, not simulated
- 🏆 1st place, LATAM-wide, at a CERN/OQI-affiliated quantum computing hackathon, a month after touching quantum computing for the first time
- 🎯 Open to Summer 2026 internships in embedded systems, robotics, and applied ML

<br>

## The Numbers

| | | |
|---|---|---|
| **126×** faster inference | measured on real ESP32 hardware (184ns vs. 23.3μs) | `IEEE CASE 2026` |
| **99.85%** accuracy | zero false positives, zero false negatives | `IEEE BDAI 2026` |
| **98.4%** less energy | edge inference vs. streaming raw data to the cloud | `IEEE BDAI 2026` |
| **1st place** | LATAM-wide, Quantum Computing for Water Challenges | `OQI Hackathon 2026` |

<br>

## Tech Stack

**Languages**
<br>
![Python](https://skillicons.dev/icons?i=python) ![Cpp](https://skillicons.dev/icons?i=cpp) ![TypeScript](https://skillicons.dev/icons?i=ts) ![JavaScript](https://skillicons.dev/icons?i=js)

**Embedded & Robotics**
<br>
![Arduino](https://skillicons.dev/icons?i=arduino) ![Raspberrypi](https://skillicons.dev/icons?i=raspberrypi)
`ESP32 (Xtensa / RISC-V)` · `FreeRTOS` · `MQTT` · `PID / LQR / Kalman Filter`

**ML, Data & Quantum**
<br>
![OpenCV](https://skillicons.dev/icons?i=opencv) ![Pandas](https://skillicons.dev/icons?i=pandas)
`scikit-learn` · `NumPy` · `Qiskit` · `PennyLane` · `PuLP / MILP`

**Web & Tools**
<br>
![Astro](https://skillicons.dev/icons?i=astro) ![React](https://skillicons.dev/icons?i=react) ![Tailwind](https://skillicons.dev/icons?i=tailwind) ![Git](https://skillicons.dev/icons?i=git) ![Figma](https://skillicons.dev/icons?i=figma)
`Fusion 360` · `MATLAB`

<br>

## Featured Projects

<details open>
<summary><b>🔬 Edge AI Decision Framework — IEEE CASE 2026</b></summary>
<br>

A stage-aware framework that switches between Random Forest and Logistic Regression based on measured fault separability (Fisher Discriminant Ratio), cutting inference cost 126× once a bearing fault is obvious, without sacrificing sensitivity during the hard-to-detect early stage. Found a real single-precision floating-point bug that flipped an SVM's decision on actual ESP32 silicon, despite a perfect AUC in simulation.

| | |
|---|---|
| **Stack** | Python · scikit-learn · ESP32 (Xtensa LX6) |
| **Validation** | 10,000 hardware runs/model, cycle-accurate latency |
| **Status** | Accepted, presenting in person, Aug 2026, Shenyang |
| **Read more** | [Case study](https://alesso-24.github.io/portfolio/project/fault-detection-case) |

</details>

<details>
<summary><b>⚙️ Predictive Maintenance at 99.85% — IEEE BDAI 2026</b></summary>
<br>

A Random Forest classifier detecting bearing faults on the NASA IMS dataset with zero false positives, light enough to run on a $5 microcontroller. An analytical energy model shows 98.4% lower energy cost than streaming raw vibration data to the cloud.

| | |
|---|---|
| **Stack** | Python · scikit-learn · ESP32 · FreeRTOS |
| **Result** | 99.85% accuracy, 0/197 misclassified |
| **Status** | Presented, IEEE BDAI 2026, Chongqing (Session Chair) |
| **Read more** | [Case study](https://alesso-24.github.io/portfolio/project/fault-detection) |

</details>

<details>
<summary><b>🥇 Quantum Computing for Puebla's Water Crisis — 1st Place, OQI Hackathon LATAM 2026</b></summary>
<br>

Modeled Puebla's real water-distribution deficit as a MILP, then reformulated it as QUBO and solved it with QAOA on IBM Qiskit. Led the MILP formulation and baseline analysis. Organized by OQI (Open Quantum Institute) with CERN representatives on the jury and QCentroid providing compute infrastructure. Won 1st place LATAM-wide.

| | |
|---|---|
| **Stack** | Python · PuLP/CBC · Qiskit · PennyLane |
| **Result** | 1st place, 3-day hackathon, cross-institution LATAM teams |
| **Repo** | [ro-sgr/OQI26-BUAP-equipo9](https://github.com/ro-sgr/OQI26-BUAP-equipo9) |
| **Read more** | [Case study](https://alesso-24.github.io/portfolio/project/quantum-water-hackathon) |

</details>

<details>
<summary><b>🏁 Tracky — High-Speed Line Follower Robot, LARC 2025</b></summary>
<br>

Custom ESP32-C6 robot with an Inertial Recovery protocol that reclaims the line in milliseconds after a lost-track event. Raced at the 25th Latin American Robotics Competition against top LATAM universities. Real-time Python telemetry dashboard for live PID tuning over BLE.

| | |
|---|---|
| **Stack** | C++ · ESP32-C6 · PID Control · Python · BLE |
| **Result** | Competed at LARC 2025, Tec de Monterrey |
| **Repo** | [Alesso-24/Tracky](https://github.com/Alesso-24/Tracky) |
| **Read more** | [Case study](https://alesso-24.github.io/portfolio/project/larc-2025) |

</details>

<details>
<summary><b>📦 AI Inventory Control with Facial Recognition</b></summary>
<br>

A modular computer-vision system that audits a tool shelf in real time: detects when an item is taken or returned, logs the event, and captures photo evidence of both the item and the person involved. Debounced scene-change detection (SSIM) avoids false triggers from lighting changes.

| | |
|---|---|
| **Stack** | Python · OpenCV · HaarCascades · Tkinter |
| **Repo** | [Alesso-24/Control-Inventario-IA](https://github.com/Alesso-24/Control-Inventario-IA) |

</details>

<br>

## Research & Publications

| # | Paper | Venue | Status |
|---|---|---|---|
| 01 | Edge AI Decision Framework: Quantifying the Sensitivity-Latency Trade-off in Industrial Bearing Predictive Maintenance | IEEE CASE 2026 | Accepted · presenting Aug 2026 |
| 02 | Comparative Evaluation of Lightweight Supervised Machine Learning Techniques for Industrial Rotating Machinery | IEEE BDAI 2026 | Presented · IEEE Xplore pending |

<br>

## GitHub Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Alesso-24&show_icons=true&count_private=true&hide_border=true&bg_color=00000000&title_color=2540C0&icon_color=EA6A2E&text_color=6F6A5F" />
<img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=Alesso-24&hide_border=true&background=00000000&stroke=00000000&ring=2540C0&fire=EA6A2E&currStreakLabel=2540C0" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Alesso-24&hide_border=true&bg_color=00000000&color=6F6A5F&line=2540C0&point=EA6A2E" width="100%"/>

</div>

<br>

## Currently

```yaml
learning:    ["advanced control theory", "quantum optimization at scale"]
building:    "the next edge-AI project that has to survive real hardware"
open_to:     ["Summer 2026 internships", "embedded/robotics/edge-AI roles",
              "international research collaborations"]
```

<br>

<div align="center">

### Let's build something real.

[![Portfolio](https://img.shields.io/badge/Portfolio-view_my_work-2540C0?style=flat-square)](https://alesso-24.github.io/portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alessandro-reyes-mtz/)
[![Email](https://img.shields.io/badge/Email-say_hello-EA6A2E?style=flat-square&logo=gmail&logoColor=white)](mailto:jordi.reyes.martinez@gmail.com)

</div>
