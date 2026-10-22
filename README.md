<h1 align="center">Diogo Silva</h1>

<p align="center">
  <b>AI/ML Engineer</b> · Intent-Based Networking · Compute Continuum · Telemetry-Driven AI
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/diogo-silva2611/"><img src="https://img.shields.io/badge/LinkedIn-Diogo%20Silva-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

---

## About

AI/ML Engineer and MSc student in **Telecommunications, Artificial Intelligence and Computer Science**.

I work on **AI-driven service optimisation across the edge–cloud continuum**. In practice, that means turning a user's high-level intent into concrete deployment and networking decisions, then using live telemetry and ML models to check those decisions against the intent and keep adjusting them.

### Current work

**Closed-loop, intent-driven orchestration across the compute continuum**

- **Intent:** translating user intents into service-level objectives and deployment policies, using intent-based and semantic networking
- **Telemetry:** collecting compute, network and application metrics from edge to cloud
- **Inference:** using ML models to forecast demand and service behaviour, and to decide where to place, scale and migrate workloads
- **Assurance:** continuously checking that the running system still satisfies the intent, balancing latency, resource utilisation and energy consumption

### Areas of interest

Intent-Based & Semantic Networking · AIOps · Edge–Cloud Orchestration · Time-Series Forecasting · Anomaly Detection · Energy-Efficient Computing

**Beyond work:** outside my core research, I'm interested in hands-on infrastructure:

- **Homelabbing & self-hosting:** virtualisation, containers and lightweight Kubernetes on bare metal, as a sandbox to build, break and rebuild systems end-to-end
- **DevOps & automation:** CI/CD pipelines, infrastructure as code and GitOps workflows
- **Observability:** metrics, logs and dashboards with Prometheus, Grafana and InfluxDB
- **IoT & home automation:** ESP32 sensor nodes, MQTT messaging and connected-home integrations

---

## Selected projects

| Project | Summary | Stack |
|---|---|---|
| [**CPU Spike Predictor**](https://github.com/DiogoZeca/Agentic_AI) | Predicts CPU spikes on datacenter machines 15–60 minutes ahead from per-machine telemetry, so a scheduler can defer, migrate or pre-empt workloads before a spike happens instead of reacting to it. Trained on Google Cluster Traces (278M rows, 12.5k machines). Transfers zero-shot to a production Slurm HPC cluster, reaching a PR-AUC of up to 0.96. | Python · XGBoost · Docker |
| [**Smart Power Fault Detection**](https://github.com/DiogoZeca/Sensor_Project) | ESP32-C6 edge node that detects brownouts and power loss in under a second. Telemetry goes over MQTT to an InfluxDB + Grafana pipeline. Uses power management to keep the CPU in light sleep more than 50% of the time with no added detection latency. | C · ESP-IDF · FreeRTOS · MQTT · InfluxDB · Grafana |
| [**Autonomous Emergency Vehicle**](https://github.com/DiogoZeca/Autonomous_Emergency_Vehicle) | V2X testbed for emergency-vehicle traffic preemption. Runs real ETSI ITS-G5 stacks (CAM, DENM, SPATEM), with road traffic simulated in SUMO, cooperative lane clearing and RSU-controlled signal preemption. | Python · SUMO · Vanetza · MQTT · Flask |
| [**UEBA Module for SIEM**](https://github.com/DiogoZeca/UEBAModule_SIEM) | Behavioural analytics engine that builds traffic baselines from network flows and flags anomalous activity and compromised devices. | Python · Network Flow Analysis |
| [**DetiCoins**](https://github.com/DiogoZeca/DetiCoins) | SHA-1 search engine implemented across scalar, AVX/AVX2/AVX-512, OpenMP, CUDA, OpenCL, MPI and WebAssembly backends, benchmarked against each other for throughput on heterogeneous hardware. | C · CUDA · OpenCL · OpenMP · MPI |

---

## Technical skills

**AI / ML & Data**

<p>
  <img src="https://skillicons.dev/icons?i=py,pytorch,tensorflow,sklearn" alt="AI/ML" />
</p>

![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=flat-square)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

**Languages & High-Performance Computing**

<p>
  <img src="https://skillicons.dev/icons?i=c,cpp,rust,java,cs,matlab" alt="Languages" />
</p>

![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![OpenCL](https://img.shields.io/badge/OpenCL-ED1C24?style=flat-square)
![OpenMP](https://img.shields.io/badge/OpenMP-1F4E79?style=flat-square)
![MPI](https://img.shields.io/badge/MPI-555555?style=flat-square)
![VHDL](https://img.shields.io/badge/VHDL-6E4C9E?style=flat-square)

**Networking, Telecom & Embedded**

![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![GNS3](https://img.shields.io/badge/GNS3-2E7D32?style=flat-square)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)
![V2X](https://img.shields.io/badge/V2X%20%2F%20ITS--G5-37474F?style=flat-square)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-3C9A3C?style=flat-square)

**Infrastructure & Observability**

<p>
  <img src="https://skillicons.dev/icons?i=docker,linux,bash,git,grafana" alt="Infrastructure" />
</p>

![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?style=flat-square&logo=influxdb&logoColor=white)

---

## Contact

Open to conversations on intent-based networking, AI for infrastructure operations and edge–cloud orchestration.
Reach me on [LinkedIn](https://www.linkedin.com/in/diogo-silva2611/).
