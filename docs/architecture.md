# LysipheN — Sanitized System Architecture

This document presents a high-level, non-confidential view of the LysipheN monitoring and automation architecture for portfolio purposes.

## System layers

### 1. Sensing and instrumentation
The system begins with physical measurements acquired from sensors such as load cells and associated instrumentation electronics. Signal acquisition is handled through ADC and embedded interfaces before the data is transmitted to higher-level software components.

### 2. Embedded processing
ESP32 and Raspberry Pi devices participate in acquisition, local processing, communication, and orchestration tasks depending on the deployment context.

### 3. Communications
MQTT and LoRaWAN are used as communication technologies within the broader monitoring workflow. The exact production topology, credentials, and internal infrastructure are intentionally omitted.

### 4. Application and automation logic
Python, JavaScript, and Node-RED are used to support automation logic, data handling, validation, and user-facing workflows.

### 5. Data storage
MySQL is used for structured data storage and retrieval as part of the monitoring workflow.

### 6. Visualization and user workflows
Dashboards and interfaces allow users to interact with monitored information and operational workflows.

## Simplified data flow

```text
Physical variable
      |
      v
Sensor / Load Cell
      |
      v
ADC / Embedded Interface
      |
      v
ESP32 / Raspberry Pi
      |
      v
MQTT / LoRaWAN
      |
      v
Python / JavaScript / Node-RED
      |
      v
MySQL
      |
      v
Dashboard / User Workflow
```

## Engineering responsibilities demonstrated

- Requirements gathering from laboratory users
- Translation of operational needs into technical requirements
- Hardware/software integration
- Data validation and troubleshooting
- Field deployment
- Preventive and corrective maintenance support
- Technical coordination and documentation

## Confidentiality note

This architecture is intentionally generalized. It does not include proprietary source code, credentials, internal IP addresses, private datasets, or confidential implementation details belonging to Alliance Bioversity International & CIAT.
