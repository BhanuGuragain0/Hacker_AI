

<p align="center">
  <img src="https://github.com/BhanuGuragain0/Hacker_AI/raw/main/docs/assets/logo.png" alt="Hacker_AI Logo" width="200"/>
</p>

<h1 align="center">Hacker_AI</h1>

<p align="center">
  <strong>Unleash the AI-Driven Cybersecurity Titan: Crush Elite Threats with Ethical Precision</strong><br>
  Forged by <a href="https://github.com/BhanuGuragain0">Bhanu Guragain</a>, BSc Ethical Hacking & Cybersecurity, Coventry University<br>
  Powered by Shadow Senior (AI Coding Beast)
</p>

<p align="center">
  <a href="https://github.com/BhanuGuragain0/Hacker_AI/actions/workflows/ci.yml">
    <img src="https://github.com/BhanuGuragain0/Hacker_AI/actions/workflows/ci.yml/badge.svg" alt="Build Status"/>
  </a>
  <a href="https://github.com/BhanuGuragain0/Hacker_AI/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/BhanuGuragain0/Hacker_AI" alt="License"/>
  </a>
  <a href="https://github.com/BhanuGuragain0/Hacker_AI/releases/latest">
    <img src="https://img.shields.io/github/v/release/BhanuGuragain0/Hacker_AI?color=blue" alt="Version"/>
  </a>
  <a href="https://github.com/BhanuGuragain0/Hacker_AI/stargazers">
    <img src="https://img.shields.io/github/stars/BhanuGuragain0/Hacker_AI?style=social" alt="Stars"/>
  </a>
  <a href="https://github.com/BhanuGuragain0/Hacker_AI/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/BhanuGuragain0/Hacker_AI?color=green" alt="Contributors"/>
  </a>
  <a href="https://github.com/BhanuGuragain0/Hacker_AI/releases">
    <img src="https://img.shields.io/github/downloads/BhanuGuragain0/Hacker_AI/total" alt="Downloads"/>
  </a>
</p>

<p align="center">
  <em>Born in Coventry University’s chaos forge, <strong>Hacker_AI</strong> is a JARVIS-grade platform—AI autonomy, stealth tactics, and self-healing resilience fused to dominate the digital battlefield.</em>
</p>

---
```markdown
## 🌐 What is Hacker_AI?

**Hacker_AI** is an AI-powered cybersecurity juggernaut built to outsmart elite threats. It hunts zero-days with `zero_day_hunter.py`, orchestrates precision strikes via `orchestration.py`, and leverages fine-tuned models such as `deepseek_coder_v2_lite_instruct` and `openthinker_32b` to dynamically coordinate and execute attacks. Born from 
academic rigor and battlefield innovation, it’s the ultimate weapon for pentesters, researchers, and defenders—ethically engineered and battle-proven.

> **Our Edge**: Shadow Junior’s technical grit meets Shadow Senior’s AI muscle, combining state-of-the-art reinforcement learning, quantum-safe cryptography, and self-healing infrastructure to crush tomorrow’s threats today.


## ✨ Killer Features
 
| Feature                   | Why It Roars                                                                                                 | Dive In                                  |
|---------------------------|--------------------------------------------------------------------------------------------------------------|------------------------------------------|
| **AI-Powered Offense**    | Autonomous exploit generation using `codebert_base.pt` & advanced PPO loops in `ai_decision.py`.             | `backend/ai_engine/exploitation/`        |
| **Zero-Day Hunting**      | ML-driven threat prediction with real-time edge, courtesy of `zero_day_hunter.py`.                           | `backend/ai_engine/zero_day/`            |
| **Self-Healing Core**     | Auto-recovery with anomaly detection (`self_heal_system.py`) ensuring 99.999% uptime.                        | `backend/core/self_healing/`             |
| **Tool Arsenal**          | 30+ wrappers for tools like Nmap, Metasploit, and Hashcat, enhanced with quantum-optimized evasion.          | `tools/`                                 |
| **Orchestration Mastery** | Fine-tuned workflow orchestration with DAGs powered by Celery/Redis and advanced models (`openthinker_32b`). | `backend/core/orchestration/`            |
| **Quantum-Safe Crypto**   | Future-proof encryption using AES-256-GCM & post-quantum algorithms.                                         | `backend/core/security/encryption.py`    |
| **Scalable Power**        | Dockerized & Kubernetes-ready architecture for rapid, global deployment.                                     | `deployment/`                            |
| **Plugin Freedom**        | Modular design allows community-driven extensions for unmatched versatility.                                 | `plugins/`                               |
|---------------------------|--------------------------------------------------------------------------------------------------------------|------------------------------------------|


```
---

## 📂 Project Structure

A 115+ directory, 418+ file titan powering a cybersecurity revolution. Here’s the core breakdown:

```bash
📁 Hacker_AI/
├─ 📊 **analytics/**  
│  🔍 Metrics collection, dashboards, data pipelines, and report generation.  
│
├─ ⚙️ **backend/**  
│  🔧 Core backend logic, AI-driven tools, and API implementation.  
│  ├─ 🤖 **ai_engine/**  
│  │  ├── 🧠 **decision_engine/**  
│  │  │  💡 Decision-making logic for AI operations and threat mapping.  
│  │  ├── 🕵️ **evasion/**  
│  │  │  🛡️ Tools for evasion techniques to bypass security measures.  
│  │  ├── 💥 **exploitation/**  
│  │  │  🪝 Modules for automated learning and exploitation strategies.  
│  │  ├── 📚 **models/**  
│  │  │  🧩 AI models, base classes, and bounty engines.  
│  │  ├── 🌐 **osint/**  
│  │  │  📰 Open-source intelligence (OSINT) engine for data gathering.  
│  │  ├── 🔓 **post_exploitation/**  
│  │  │  🔑 Tools for post-exploitation activities.  
│  │  ├── 📦 **pre_trained_models/**  
│  │  │  🧠 Pre-trained AI models like CodeBERT, VulnBERT, and Vulnerability Predictor.  
│  │  ├── 🔎 **reconnaissance/**  
│  │  │  🕵️ Reconnaissance tools for scanning and intelligence gathering.  
│  │  ├── 🎯 **red_teaming/**  
│  │  │  🎭 Red teaming simulation and threat modeling.  
│  │  ├── 📝 **strategies/**  
│  │  │  🧠 AI strategies like hyperdimensional computing and neuroplasticity.  
│  │  ├── 🏋️ **trainers/**  
│  │  │  🏅 Training methodologies such as adversarial and federated learning.  
│  │  ├── ⏱️ **training_pipeline/**  
│  │  │  🛠️ Pipelines for training tools like Nmap and SQLMap.  
│  │  ├── **vulnerability_assessment/**  
│  │  │  🛡️ Tools for assessing system vulnerabilities.  
│  │  └── 💣 **zero_day/**  
│  │     🚀 Zero-day vulnerability hunting and prediction.  
│  │
│  ├─ 🌐 **api/**  
│  │  🌍 Backend API implementation with routes, middleware, and monitoring.  
│  │  ├── 🛡️ **middleware/**  
│  │  │  🛠️ Middleware for error handling, input validation, and rate limiting.  
│  │  ├── 📈 **monitoring/**  
│  │  │  🩺 Health checks and performance metrics.  
│  │  └── 🚦 **routes/**  
│  │     🛣️ API routes for bounty, exploit, intelligence, and scan functionalities.  
│  │
│  ├─ 🏛️ **core/**  
│  │  🧱 Core components of the backend system.  
│  │  ├── ❗ **exceptions/**  
│  │  │  ⚠️ Custom exceptions for API, database, and tools.  
│  │  ├── 🔄 **migrations/**  
│  │  │  📦 Database migration scripts managed by Alembic.  
│  │  │  └── **versions/**  
│  │  │     📝 Migration versions.  
│  │  ├── 🗄️ **models/**  
│  │  │  🗂️ Data models for exploit results, scan results, users, and vulnerabilities.  
│  │  ├── 🔧 **orchestration/**  
│  │  │  🎶 Orchestration logic for AI models like DeepSeek, Llama, and SecurityLLM.  
│  │  │  ├── **deepseek_coder_v2_lite_instruct/**  
│  │  │  │  🧠 Configuration and model files for DeepSeek Coder.  
│  │  │  ├── **deepseek_r1_distill_qwen_32b/**  
│  │  │  │  🧠 Configuration and model files for DeepSeek R1.  
│  │  │  ├── **llama/**  
│  │  │  │  🦙 Configuration and model files for Llama.  
│  │  │  ├── **openthinker_32b/**  
│  │  │  │  🧠 Configuration and model files for OpenThinker 32B.  
│  │  │  ├── **openthinker_7b/**  
│  │  │  │  🧠 Configuration and model files for OpenThinker 7B.  
│  │  │  └── **securityllm/**  
│  │  │     🛡️ Configuration and model files for SecurityLLM.  
│  │  ├── 🔒 **security/**  
│  │  │  🛡️ Security utilities like access control, authentication, and encryption.  
│  │  ├── 💊 **self_healing/**  
│  │  │  🩹 Self-healing mechanisms for anomaly detection and recovery.  
│  │  └── 🔧 **utils/**  
│  │     🛠️ Utility functions for data processing and network operations.  
│  │
│  └─ 🧪 **experiments/**  
│     🔬 Experimental features and quantum testing.  
│
├─ 📊 **benchmarks/**  
│  📈 Benchmarking tools for performance, scalability, and resource usage.  
│
├─ ⚙️ **config/**  
│  🛠️ Configuration files for the application.  
│  └── **env/**  
│     ├── **dev/**  
│     │  🛠️ Development environment configurations.  
│     └── **prod/**  
│        🛠️ Production environment configurations.  
│
├─ 📁 **data/**  
│  🗄️ Data storage and processing.  
│  ├── **backup/**  
│  │  💾 Backup files.  
│  ├── **datasets/**  
│  │  ├── **encrypted/**  
│  │  │  🔐 Encrypted datasets.  
│  │  ├── **openthoughts_114k/**  
│  │  │  📚 A large dataset split into training and metadata files.  
│  │  └── **raw/**  
│  │     📂 Raw datasets.  
│  ├── **db/**  
│  │  🗃️ Database-related files.  
│  ├── **exploits/**  
│  │  💣 Exploit-related files.  
│  ├── **migrations/**  
│  │  📦 Database migration scripts.  
│  ├── **payloads/**  
│  │  📦 Payload files.  
│  ├── **pipeline/**  
│  │  🛠️ Data pipeline components for ingestion, processing, and storage.  
│  └── **wordlists/**  
│     📋 Wordlists for various purposes.  
│
├─ 🚀 **deployment/**  
│  🚢 Deployment configurations for Docker and Kubernetes.  
│  ├── **docker/**  
│  │  ├── **backend/**  
│  │  │  🐳 Docker setup for the backend.  
│  │  ├── **frontend/**  
│  │  │  🐳 Docker setup for the frontend.  
│  ├── **kubernetes/**  
│  │  🚢 Kubernetes deployment files.  
│
├─ 📚 **docs/**  
│  📖 Documentation files for APIs, deployment, and developer guides.  
│
├─ 🖥️ **frontend/**  
│  🖼️ Frontend components for CLI, GUI, and web UI.  
│  ├── **cli/**  
│  │  🖥️ Command-line interface tools.  
│  │  ├── **other_clis/**  
│  │  │  🖥️ Miscellaneous CLI tools.  
│  │  └── **tool_clis/**  
│  │     🖥️ CLI wrappers for tools like Nmap, Metasploit, and SQLMap.  
│  ├── **gui/**  
│  │  🖼️ Graphical user interface components.  
│  └── **web_ui/**  
│     🌐 Web-based user interface with React components and styles.  
│
├─ 📜 **.github/**  
│  🤖 GitHub Actions workflows for CI/CD and security scans.  
│  └── **workflows/**  
│     🛠️ Workflow files for continuous integration and deployment.  
│
├─ **logs/**  
│  📝 Log files for debugging and monitoring.  
│
├─ 🔌 **plugins/**  
│  🧩 Plugin system for integrating additional tools.  
│  └── **tools_plugin/**  
│     🛠️ Plugins for tools integration.  
│
├─ 🧪 **sandbox/**  
│  🧪 Experimental features and testing ground.  
│
├─ 📜 **scripts/**  
│  🛠️ Utility scripts for backup, deployment, setup, and updates.  
│
├─ 🔑 **secret/**  
│  🔐 Secret data and configurations.  
│  └── **data/**  
│     ├── **backend/**  
│     │  🔐 Backend secrets (e.g., AI models, database credentials).  
│     ├── **frontend/**  
│     │  🔐 Frontend secrets (e.g., API keys, session data).  
│     └── **tools/**  
│        🔐 Tool-specific secrets (e.g., Metasploit, Nmap, Shodan).  
│
├─ 🧪 **tests/**  
│  🧪 Test cases for AI engine and API components.  
│  ├── **ai_engine/**  
│  │  🧠 Tests for AI engine modules.  
│  └── **api/**  
│     🌐 Tests for API routes and functionality.  
│
└─ 🛠️ **tools/**  
   🛠️ Wrappers for various cybersecurity tools.  
   ├── **cloud/**  
   │  ☁️ Cloud-related tools (e.g., AWS, Azure).  
   ├── **crypto_stego/**  
   │  🔐 Cryptography and steganography tools.  
   ├── **database/**  
   │  🗄️ Database tools (e.g., SQLMap, NoSQLMap).  
   ├── **evasion/**  
   │  🛡️ Evasion tools (e.g., Veil, Shellter).  
   ├── **exploitation/**  
   │  💥 Exploitation tools (e.g., Metasploit, Cobalt Strike).  
   ├── **fuzzing/**  
   │  🧪 Fuzzing tools (e.g., AFL, Boofuzz).  
   ├── **gpu/**  
   │  💻 GPU-related tools (e.g., Hashcat).  
   ├── **hardware/**  
   │  🛠️ Hardware tools (e.g., ChipWhisperer).  
   ├── **identify/**  
   │  🔍 Identification tools (e.g., Nmap OS detection).  
   ├── **information_gathering/**  
   │  🕵️ Information-gathering tools (e.g., Nmap, Shodan).  
   ├── **iot/**  
   │  📱 IoT-related tools.  
   ├── **other_tools/**  
   │  🛠️ Miscellaneous tools.  
   ├── **passwords/**  
   │  🔑 Password-cracking tools (e.g., Hydra, John).  
   ├── **post_exploitation/**  
   │  🔓 Post-exploitation tools (e.g., Mimikatz, BloodHound).  
   ├── **recovery/**  
   │  💾 Data recovery tools (e.g., PhotoRec).  
   ├── **reverse_engineering/**  
   │  🔧 Reverse engineering tools (e.g., Ghidra, IDA Pro).  
   ├── **rfid/**  
   │  📡 RFID tools (e.g., Proxmark).  
   ├── **sdr/**  
   │  📻 Software-defined radio tools (e.g., GQRX).  
   ├── **smartphones/**  
   │  📱 Smartphone-related tools.  
   ├── **sniffing_spoofing/**  
   │  📡 Sniffing and spoofing tools (e.g., Wireshark, Ettercap).  
   ├── **social_engineering/**  
   │  🎭 Social engineering tools (e.g., SET).  
   ├── **voip/**  
   │  📞 VoIP tools (e.g., SIPVicious).  
   ├── **vulnerability/**  
   │  🛡️ Vulnerability scanning tools (e.g., Nessus, OpenVAS).  
   ├── **web/**  
   │  🌐 Web-related tools (e.g., Burp Suite, Nikto).  
   └── **wireless/**  
      📶 Wireless tools (e.g., Aircrack, Wifite).

```

**Full Beast**: Dive into the repo for all files powering this revolution!

---

## 💻 System Requirements

- **OS**: Linux (Ubuntu 20.04+ preferred), macOS, or Windows (WSL2)
- **Python**: 3.9+
- **Node.js**: 16+ (for web UI)
- **Docker**: 20.10+ (optional, for containerized deployment)
- **Hardware**:
  - **Minimum**: 8GB RAM, 4-core CPU, 20GB storage
  - **Recommended**: 32GB RAM, NVIDIA GPU (CUDA 11+), 100GB SSD
- **Prerequisites**: Ensure nmap, metasploit-framework, and hashcat are in your PATH

---

## 🛠️ Installation & Quick Start

1. **Clone the Titan**:
   ```bash
   git clone https://github.com/BhanuGuragain0/Hacker_AI.git
   cd Hacker_AI
   ```
2. **Set Up Environment**:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate   # Windows: .venv\Scripts\activate
   pip install -r requirements.txt
   cp config/env/dev/secrets.env .env
   nano .env  # Configure API keys, DB credentials, etc.
   ```
3. **Unleash the Beast**:
   ```bash
   python3 launcher.py
   ```

---

## 🎮 Usage Examples

### CLI Strike
**Scan with AI**:
```bash
python3 frontend/cli/main_cli.py scan --target 192.168.1.1 --ai  # If python3 isn't working then use python 
```
_Output:_
```
🔍 Scanning 192.168.1.1...
🤖 AI: Port 22 (SSH) open - Weak authentication detected.
🔒 Report: reports/scan_192.168.1.1.enc
```

**Run Nmap**:
```bash
python3 frontend/cli/tool_clis/nmap_cli.py -sV 192.168.1.1
```

### GUI & Web Interface
- **Launch Dashboard**:
  ```bash
  python3 frontend/gui/dashboard.py
  ```
- **Start Web UI**:
  ```bash
  cd frontend/web_ui
  npm install && npm start
  ```
  _Visit [http://localhost:3000](http://localhost:3000)_

### API Control
- **Start API Server**:
  ```bash
  python3 backend/api/server.py
  ```
- **Test API**:
  ```bash
  curl http://localhost:8000/api/scan
  ```

### Orchestrate Chaos
- **Execute a Workflow**:
  ```bash
  python3 backend/core/orchestration/orchestration.py --task scan --target 192.168.1.1
  ```

### Training the Beast
- **Fine-Tune openthinker_32b**:
  ```bash
  python3 backend/ai_engine/trainers/adversarial.py --model backend/core/orchestration/openthinker_32b/
  ```

---

## 🧪 Testing & Deployment

- **Run All Tests**:
  ```bash
  pytest tests/ -v --cov
  ```
- **Docker Deployment**:
  ```bash
  cd deployment/docker/backend
  docker-compose up --build
  ```
- **Kubernetes Deployment**:
  ```bash
  kubectl apply -f deployment/kubernetes/backend_deployment.yaml
  ```

---

## 🤝 Contributing

1. **Fork & Clone**: `git checkout -b feat/your-enhancement`
2. **Hack It**: Enhance components like `orchestration.py` or add new tool wrappers (e.g., `tools/burpsuite_warper.py`)
3. **Submit a PR**: Join the revolution!

---

## 🛤️ Roadmap

- **Q2 2025**: GPU-accelerated training for deepseek_* models (CUDA 11+)
- **Q3 2025**: Integration of a Burp Suite wrapper for web attack automation
- **Q4 2025**: Real-time, WebSocket-powered GUI updates in `dashboard.py`
- **2026**: Cloud-scale deployment across AWS/Azure using tools in `tools/cloud/`

---

## 🌟 Why Hacker_AI?

- **AI Muscle**: Fine-tuned models like openthinker_32b deliver unparalleled predictive power.
- **Ethical Core**: Student-built for legal, responsible cyber defense and offense.
- **Community Power**: Open-source, plugin-ready architecture invites global collaboration.
- **Future-Ready**: Quantum-safe, self-healing, and adaptively resilient against evolving threats.

---

## 📜 License

Released under the **MIT License** – unleash it freely!

---

## 📬 Contact

- **Bhanu Guragain**: guragainbhanu802@gmail.com  
- **GitHub**: [Issues](https://github.com/BhanuGuragain0/Hacker_AI/issues)  
- **Discord**: Join our community (details TBD)

---

<p align="center">
  <strong>Hacker_AI: Where Student Grit Meets AI-Powered Cyber Dominance.</strong>
</p>

