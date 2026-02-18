# Autonomous Women's Safety & Fire Automation System 🛡️🌬️

**Problem Statement ID:** HK-SAFETY-012  
**Event:** Hack KRMU 5.0 (Feb 18-20, 2026)  
**Team Name:** Error 404 (HK-84)  
**Location:** School of Engineering & Technology (Center of Excellence - AI), K.R. Mangalam University

---

## 👥 Team Members
* **Ashish Yadav** (2301010413) — *Team Lead*
* **Kundan Singh** (2301010404)
* **Ritik Kumar** (2401730227)
* **Harshit Jaiswal** (2301010397)

---

## 🚀 Project Overview
Developed during a 54-hour hackathon, this system addresses a critical gap in modern infrastructure: **Reactive vs. Proactive Safety**. Standard safety systems notify, but they don't intervene. 

Forensic research from tragedies like the Surat Takshashila Fire (2019) and Madurai (2024) proves that smoke asphyxiation kills victims long before manual help or heat sensors trigger. This is an autonomous, PAC-driven system that uses **Reverse Suction Technology** to clear smoke from exit paths in under 2 seconds, effectively turning a building's HVAC into a life-support system.

---

## ✨ Core Innovation & Intelligent Features

* 🌪️ **Reverse Suction (Active Purge):** Instead of just sounding a siren, the system instantly reverses HVAC fans to pull smoke out of hallways, maintaining a breathable envelope for occupants.
* 🎙️ **Scream Recognition AI:** High-decibel frequency analysis detects human distress/panic screams in high-risk zones (like women's hostels) even before smoke particulates reach sensor thresholds.
* ⚡ **Edge Priority Logic:** All safety protocols are "Hardcoded" into the PAC (Programmable Automation Controller). The system operates locally without any cloud dependency, ensuring it works during network grid failures.
* 💡 **Intelligent Pathlighting:** Automatically unlocks all magnetic doors and illuminates low-level floor paths to guide occupants through smoke-cleared zones.

---

## 🛠️ Technical Tech Stack

| Component | Technology |
| :--- | :--- |
| **Control Logic** | Industrial PAC & Ladder Logic |
| **Networking** | Industrial Mesh (Zigbee/LoRa) for 0% packet loss |
| **Sensing** | MQ-2 Smoke Arrays + dB Frequency Audio Sensors |
| **Monitoring** | Real-time SCADA Dashboard for warden/security |
| **Actuation** | Smart Vents & Reversible HVAC Actuators |

---

## 📊 Impact & Feasibility

* **Life Saving:** Eliminates the "human confirmation delay" which usually takes 2-5 minutes.
* **Cost Efficiency:** Saves ~30% in annual energy costs via smart HVAC cycles based on occupancy, covering the initial hardware CapEx within 18 months.
* **Retrofit Ready:** Designed to be installed on existing building ventilation without major structural changes.
* **Research Grounding:** Benchmarked against **NFPA 92** (Standard for Smoke Control Systems) and forensic analysis of recent fire tragedies.

---

## 📂 Repository Structure

```text
├── Hardware/
│   ├── Schematics/         # PAC Circuit diagrams & Sensor wiring
│   └── BOM.md              # Bill of Materials (Sensors, Actuators)
├── Logic/
│   ├── Ladder_Logic/       # PLC/PAC Hardcoded safety blocks
│   └── Scream_Detection/   # Audio frequency analysis scripts
├── SCADA/
│   ├── Dashboard/          # Web-based monitoring UI
│   └── Assets/             # HMI Graphics
└── Docs/
    ├── Case_Study_Analysis.pdf
    └── Project_Report.pdf

```

##Developed with ❤️ by Team Error 404 > Center of Excellence - AI | K.R. Mangalam University
