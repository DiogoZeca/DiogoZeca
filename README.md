<h1 align="center">Hi, I'm Diogo Silva 👋</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&pause=1200&color=3B82F6&center=true&vCenter=true&width=640&lines=AI%2FML+Engineer;Network+Infrastructure+%C2%B7+Wi-Fi+%C2%B7+5G;AI-driven%2C+energy-aware+service+optimisation;MSc+in+Telecom%2C+AI+%26+Computer+Science" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,pytorch,tensorflow,c,cpp" alt="Python, PyTorch, TensorFlow, C, C++" /><img src="assets/cuda.svg" height="48" alt="CUDA" /><img src="https://skillicons.dev/icons?i=rust,java,matlab,docker,linux,grafana" alt="Rust, Java, MATLAB, Docker, Linux, Grafana" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/diogo-silva2611/"><img src="https://img.shields.io/badge/LinkedIn-Diogo%20Silva-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

---

## About

I'm an AI/ML Engineer in **Telecommunications, Artificial Intelligence and Computer Science**.

My background is in **networking**: network infrastructure, Wi-Fi and 5G. That's still where I work, but now I'm applying **AI/ML** on top of it. I use it to turn a user's intent into network and service configuration, and to turn telemetry into decisions that **optimise those services and make them more energy-efficient**, so they deliver the same quality with a smaller footprint.

### Current work

**Intent-driven, energy-aware service optimisation across the edge–cloud continuum**

- **Intent:** translating user intents into service-level objectives and network and deployment policies, using intent-based and semantic networking
- **Telemetry:** collecting network, compute and application telemetry from edge to cloud
- **Optimisation:** using ML models to forecast demand and service behaviour, then placing, scaling and migrating services to where they run most efficiently, cutting wasted resources and energy without breaking SLOs
- **Closed loop:** continuously checking that the running system still meets the intent, and reacting to drift, faults and anomalies before they reach the user

### Toolbox

- **Networking & Telecom:** network infrastructure, Wi-Fi (IEEE 802.11), 5G, V2X / ETSI ITS-G5, Wireshark, GNS3, MQTT
- **ML & Data:** PyTorch, TensorFlow, XGBoost, pandas, NumPy, Jupyter, pytest
- **Systems & HPC:** Python, C/C++, Rust, Java, C#, MATLAB, CUDA, OpenCL, OpenMP, MPI, VHDL
- **Cybersecurity & SIEM:** Wazuh, Suricata, UEBA, network threat detection (data exfiltration, DNS tunnelling, C2 beaconing), GeoIP enrichment
- **Observability:** Grafana, InfluxDB, Telegraf, Prometheus, MQTT telemetry pipelines
- **DevOps & Automation:** Linux, Docker, Docker Compose, Git, GitHub Actions (CI/CD), Bash scripting
- **Embedded:** ESP32, ESP-IDF, FreeRTOS

### Areas of interest

Intent-Based & Semantic Networking · 5G & Wireless Networks · AI for Network Operations · Network Telemetry · Green & Energy-Efficient Networking · Edge–Cloud Orchestration · Network Security

**Beyond work:** outside my core research, I'm interested in hands-on infrastructure:

- **Homelabbing & self-hosting:** virtualisation, containers and lightweight Kubernetes on bare metal, as a sandbox to build, break and rebuild systems end-to-end
- **IoT & home automation:** ESP32 sensor nodes, MQTT messaging and connected-home integrations


---

## Selected projects

| Project | Summary | Stack |
|---|---|---|
| [**CPU Spike Predictor**](https://github.com/DiogoZeca/Agentic_AI) | Predicts CPU spikes on datacenter machines 15–60 minutes ahead from per-machine telemetry, so a scheduler can defer, migrate or pre-empt workloads before a spike happens instead of reacting to it. Trained on Google Cluster Traces (278M rows, 12.5k machines). Transfers zero-shot to a production Slurm HPC cluster, reaching a PR-AUC of up to 0.96. | Python · XGBoost · Docker |
| [**Smart Power Fault Detection**](https://github.com/DiogoZeca/Sensor_Project) | ESP32-C6 edge node that detects brownouts and power loss in under a second. Telemetry goes over MQTT to an InfluxDB + Grafana pipeline. Uses power management to keep the CPU in light sleep more than 50% of the time with no added detection latency. | C · ESP-IDF · FreeRTOS · MQTT · InfluxDB · Grafana |
| [**Autonomous Emergency Vehicle**](https://github.com/DiogoZeca/Autonomous_Emergency_Vehicle) | V2X testbed for emergency-vehicle traffic preemption. Runs real ETSI ITS-G5 stacks (CAM, DENM, SPATEM), with road traffic simulated in SUMO, cooperative lane clearing and RSU-controlled signal preemption. | Python · SUMO · Vanetza · MQTT · Flask |
| [**UEBA Module for SIEM**](https://github.com/DiogoZeca/UEBAModule_SIEM) | User and Entity Behaviour Analytics module for a SIEM. It learns per-device traffic baselines from network flows and detects compromised hosts through HTTPS/QUIC data exfiltration, DNS tunnelling, connections to never-seen countries (GeoIP) and botnet C2 beaconing. | Python · Wazuh · GeoIP · Network Flow Analysis |
| [**DetiCoins**](https://github.com/DiogoZeca/DetiCoins) | SHA-1 search engine implemented across scalar, AVX/AVX2/AVX-512, OpenMP, CUDA, OpenCL, MPI and WebAssembly backends, benchmarked against each other for throughput on heterogeneous hardware. | C · CUDA · OpenCL · OpenMP · MPI |
