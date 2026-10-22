<h1 align="center">Hi, I'm Diogo Silva 👋</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&pause=1200&color=3B82F6&center=true&vCenter=true&width=640&lines=AI%2FML+Engineer;Intent-Based+%26+Semantic+Networking;Telemetry-driven+AI+across+the+compute+continuum;MSc+in+Telecom%2C+AI+%26+Computer+Science" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,pytorch,tensorflow,sklearn,c,cpp,rust,java,matlab,docker,linux,grafana&perline=12" alt="Tech stack" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/diogo-silva2611/"><img src="https://img.shields.io/badge/LinkedIn-Diogo%20Silva-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

---

## About

I'm an AI/ML Engineer and MSc student in **Telecommunications, Artificial Intelligence and Computer Science**.

I work on **AI-driven service optimisation across the edge–cloud continuum**. In practice, that means turning a user's high-level intent into concrete deployment and networking decisions, then using live telemetry and ML models to check those decisions against the intent and keep adjusting them.

### Current work

**Closed-loop, intent-driven orchestration across the compute continuum**

- **Intent:** translating user intents into service-level objectives and deployment policies, using intent-based and semantic networking
- **Telemetry:** collecting compute, network and application metrics from edge to cloud
- **Inference:** using ML models to forecast demand and service behaviour, and to decide where to place, scale and migrate workloads
- **Assurance:** continuously checking that the running system still satisfies the intent, balancing latency, resource utilisation and energy consumption

### Toolbox

- **ML & Data:** PyTorch, TensorFlow, scikit-learn, XGBoost, pandas, NumPy, Jupyter, pytest
- **Systems & HPC:** Python, C/C++, Rust, Java, C#, MATLAB, CUDA, OpenCL, OpenMP, MPI, VHDL
- **Networking & Embedded:** Wireshark, GNS3, MQTT, V2X / ETSI ITS-G5, ESP32, FreeRTOS
- **Infrastructure & Observability:** Docker, Linux, Bash, Git, Grafana, InfluxDB

### Areas of interest

Intent-Based & Semantic Networking · AIOps · Edge–Cloud Orchestration · Time-Series Forecasting · Anomaly Detection · Energy-Efficient Computing

**Beyond work:** outside my core research, I'm interested in hands-on infrastructure:

- **Homelabbing & self-hosting:** virtualisation, containers and lightweight Kubernetes on bare metal, as a sandbox to build, break and rebuild systems end-to-end
- **DevOps & automation:** CI/CD pipelines, infrastructure as code and GitOps workflows
- **Observability:** metrics, logs and dashboards with Prometheus, Grafana and InfluxDB
- **IoT & home automation:** ESP32 sensor nodes, MQTT messaging and connected-home integrations

Always happy to talk about intent-based networking, AI for infrastructure operations or edge–cloud orchestration. Feel free to reach out on [LinkedIn](https://www.linkedin.com/in/diogo-silva2611/).

---

## Selected projects

| Project | Summary | Stack |
|---|---|---|
| [**CPU Spike Predictor**](https://github.com/DiogoZeca/Agentic_AI) | Predicts CPU spikes on datacenter machines 15–60 minutes ahead from per-machine telemetry, so a scheduler can defer, migrate or pre-empt workloads before a spike happens instead of reacting to it. Trained on Google Cluster Traces (278M rows, 12.5k machines). Transfers zero-shot to a production Slurm HPC cluster, reaching a PR-AUC of up to 0.96. | Python · XGBoost · Docker |
| [**Smart Power Fault Detection**](https://github.com/DiogoZeca/Sensor_Project) | ESP32-C6 edge node that detects brownouts and power loss in under a second. Telemetry goes over MQTT to an InfluxDB + Grafana pipeline. Uses power management to keep the CPU in light sleep more than 50% of the time with no added detection latency. | C · ESP-IDF · FreeRTOS · MQTT · InfluxDB · Grafana |
| [**Autonomous Emergency Vehicle**](https://github.com/DiogoZeca/Autonomous_Emergency_Vehicle) | V2X testbed for emergency-vehicle traffic preemption. Runs real ETSI ITS-G5 stacks (CAM, DENM, SPATEM), with road traffic simulated in SUMO, cooperative lane clearing and RSU-controlled signal preemption. | Python · SUMO · Vanetza · MQTT · Flask |
| [**UEBA Module for SIEM**](https://github.com/DiogoZeca/UEBAModule_SIEM) | Behavioural analytics engine that builds traffic baselines from network flows and flags anomalous activity and compromised devices. | Python · Network Flow Analysis |
| [**DetiCoins**](https://github.com/DiogoZeca/DetiCoins) | SHA-1 search engine implemented across scalar, AVX/AVX2/AVX-512, OpenMP, CUDA, OpenCL, MPI and WebAssembly backends, benchmarked against each other for throughput on heterogeneous hardware. | C · CUDA · OpenCL · OpenMP · MPI |
