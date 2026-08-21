# LysipheN — IoT Monitoring & Automation System

LysipheN is an IoT-based monitoring system developed in the Alliance Bioversity International & CIAT environment to modernize gravimetric monitoring workflows by integrating sensing, embedded systems, data processing, databases, communications, and visualization.

> **Portfolio note:** This repository documents my engineering contribution and a sanitized view of the system architecture. Proprietary source code, credentials, internal datasets, and confidential implementation details are intentionally excluded.

## Why this project matters

This project represents my experience working across the full lifecycle of a technical solution: understanding operational needs, translating them into technical requirements, integrating hardware and software, validating data flows, troubleshooting field issues, and supporting deployment.

## My contribution

- Gathered and consolidated **52 internal laboratory requests**, translating operational needs into technical requirements for automation, monitoring, and digital tools.
- Designed, integrated, and deployed **40 LysipheN monitoring units** across Colombia and Guatemala.
- Worked with **Python, JavaScript, Node-RED, MySQL, MQTT, Raspberry Pi, and ESP32** in automation and monitoring workflows.
- Validated the end-to-end data chain from sensing and embedded processing to database storage and dashboard visualization.
- Participated in calibration, functional testing, troubleshooting, preventive/corrective maintenance, and system redesign.
- Deployed a **45-node LoRaWAN network** in a field environment spanning more than 20 km, coordinating 2 technicians and training 2 additional team members.

## Technology stack

| Area | Technologies / Concepts |
| --- | --- |
| Programming | Python, JavaScript |
| Data | MySQL, data processing, CSV workflows |
| Automation | Node-RED |
| Embedded systems | Raspberry Pi, ESP32 |
| Communication | MQTT, LoRaWAN |
| Instrumentation | Load cells, ADC, sensors |
| Delivery | Requirements gathering, troubleshooting, technical documentation, deployment |

## High-level architecture

```text
Sensors / Load Cells
        |
        v
  Embedded Device
 (ESP32 / Raspberry Pi)
        |
        v
 Communication Layer
  (MQTT / LoRaWAN)
        |
        v
 Data Processing / Logic
 (Python / JavaScript / Node-RED)
        |
        v
      MySQL
        |
        v
 Dashboard / User Workflow
```

A more detailed, sanitized architecture description is available in [`docs/architecture.md`](docs/architecture.md).

## Engineering workflow

1. Collect operational needs from laboratory users.
2. Convert those needs into technical requirements.
3. Design or modify the automation/data workflow.
4. Integrate sensors, embedded devices, communication, and software.
5. Validate the complete data path.
6. Troubleshoot failures and iterate on the design.
7. Deploy and document the resulting solution.

## What this project demonstrates

- Python and software-assisted automation
- Requirements gathering and technical translation
- Data pipelines and database interaction
- Hardware/software systems integration
- Troubleshooting across multiple system layers
- User-facing workflow design
- Field deployment and multidisciplinary coordination

## Repository scope

This repository is intended as a professional portfolio case study. It does **not** reproduce proprietary CIAT code or internal data. Public examples added here are sanitized or independently reconstructed to demonstrate engineering concepts without exposing confidential information.

## About me

**Sofía Hurtado Ramos** — Mechatronics Engineer focused on Python, automation, systems integration, and technical problem solving.

- [LinkedIn](https://www.linkedin.com/in/sofihrg/)
- [GitHub](https://github.com/MKBySofihrg)
