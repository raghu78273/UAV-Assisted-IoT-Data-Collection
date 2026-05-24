# UAV-Assisted IoT Data Collection in Infrastructure-Free Environments

## Overview
This project presents a **UAV-assisted IoT data collection framework** for 
infrastructure-free environments where traditional network connectivity is 
unavailable. UAVs act as mobile data collectors, visiting IoT sensor nodes 
and gathering data using **Delay-Tolerant Networking (DTN)** based 
communication protocols with adaptive path planning and ML-based 
intelligence.

## Objective
- Design an efficient UAV-based data collection system for remote IoT 
  sensor networks
- Minimize UAV energy consumption while maximizing data collection coverage
- Implement intelligent path planning using machine learning
- Evaluate performance across multiple routing and scheduling scenarios

## Workflow

IoT Sensor Nodes (deployed in the field)
↓
UAV detects and prioritizes nodes (ML-based)
↓
UAV flies optimized path (Energy-Aware Replanning)
↓
Data collected via DTN communication
↓
Multi-UAV coordination for full coverage
↓
Performance was evaluated across routing scenarios

## Key Algorithms
| Algorithm | Description |
|-----------|-------------|
| Energy-Aware Replanning | UAV dynamically replans path based on remaining battery |
| Multi-UAV Coordinated Coverage | Multiple UAVs coordinate to cover all sensor nodes |
| ML-based Node Prioritization | Machine learning prioritizes high-value sensor nodes |
| DTN Routing | Delay-tolerant communication for intermittent connectivity |

## Technologies Used
- **HTML5, JavaScript** — browser-based interactive simulation
- **DTN Protocol** — delay-tolerant networking for data transfer
- **Machine Learning** — intelligent node prioritization
- **Path Planning Algorithms** — optimized UAV routing
- **Multi-UAV Coordination** — distributed coverage strategies

## How to Run Simulation
1. Download `IOT UAV SIMULATION347.html.`
2. Open it in any browser (Chrome recommended)
3. Interact with the UAV path planning simulation directly —
   No installation required

## Applications
- **Disaster Monitoring** — collect sensor data in disaster zones 
  with no network infrastructure
- **Smart Agriculture** — monitor soil, temperature, and humidity 
  sensors across large farmlands
- **Remote Sensing** — gather environmental data from inaccessible 
  or hazardous areas
- **Environmental Monitoring** — track pollution, wildlife, and 
  climate parameters in forests and oceans
- **Infrastructure-Free Communication** — enable data collection in 
  military, border, and rural areas with zero connectivity
- **Search and Rescue** — locate and monitor victims using UAV-IoT 
  integration in emergency scenarios

## Future Scope
- Real hardware implementation using ESP32-based IoT nodes and 
  actual drone platforms
- Integration with deep reinforcement learning for smarter 
  UAV path planning
- Energy harvesting techniques for extended UAV flight time
- 5G and LoRaWAN communication integration for wider coverage
- Real-time cloud dashboard for live sensor data visualization
- Swarm intelligence algorithms for large-scale multi-UAV deployment

## Project Files
| File | Description |
|------|-------------|
| `IOT UAV SIMULATION347.html` | Interactive browser-based simulation |
| `IOT_UAV2026_PPT.pdf` | Project presentation slides |
| `IOT TERM PAPER.pdf` | Detailed term paper |
| `IOT BASE PAPER.pdf` | Reference base paper |

## Author
**Sarisa Raghuveer** — B.Tech ECE, IIIT Sri City (2023–2027)
