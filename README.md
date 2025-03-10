
<p align="center">
  <strong>Autonomous AI</strong><br>
  Forged by [Shadow@Bh4nu (Bhanu Guragain)](https://github.com/BhanuGuragain0), BSc Ethical Hacking & Cybersecurity, Coventry University<br>
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
  <em>
    Engineered at Coventry University's Student Cyber Lab, <strong>Hacker_AI</strong> is a self-evolving, AI-powered war machine built to preempt, counter, and annihilate cyber threats before they surface. With a modular design integrating autonomous decision-making, quantum-resistant cryptography, and self-healing infrastructure, Hacker_AI redefines the limits of digital warfare.
  </em>
</p>

---
## 🚀 Mission & Vision

**Hacker_AI** is more than a cybersecurity tool—it’s an evolving digital combat system that generates alien-level code. Our platform harnesses an ecosystem of piece-of-code generators, fine-tuned models, and pre-trained architectures to autonomously produce production-grade code that:
- **Outpaces Threats:** Predicts and neutralizes cyber attacks up to 60 seconds before execution.
- **Operates Beyond Human Intelligence:** Self-learns, adapts, and integrates future quantum modules for next-generation operations.
- **Maintains Modular Resilience:** Every component is designed to be replaceable and upgradeable without disrupting the entire system.
- **Commands in Multiple Modalities:** Run autonomously, via CLI, or even through voice commands.

Together, we’re building a system that not only meets today’s cybersecurity challenges but establishes the blueprint for a Type 3 civilization in digital warfare.

---

## 🔥 Core Cyberwar Arsenal

### 1. AGI War Core (backend/ai_engine/)
- **Autonomous Decision Engine:**  
  - *ai_decision.py*: Integrates VulnBERT with a custom PPO reinforcement learning loop to predict and counter threats.
  - *threat_mapper.py*: Converts global cyber intelligence into precise MITRE ATT&CK mappings.
- **Zero-Day Execution & Adaptive Exploitation:**  
  - *zero_day_hunter.py*: Utilizes quantum-optimized ML pipelines for real-time exploit generation.
  - *auto_learning.py*: Continuously evolves tactics based on encrypted, real-world feedback.
- **Multi-Model Integration:**  
  - Seamlessly integrates code snippets, fine-tuned models, and state-of-the-art pre-trained architectures (e.g., CodeBERT, DeepSeek, OpenThinker) to ensure an ever-adaptive system.
- **Experimental Modules:**  
  - *jarvis/*: A sandbox for advanced and experimental code (including voice command integration).  
  - *quantum/*: Future quantum AI modules for next-gen cyber offense and defense.

### 2. Stealth & Destruction Layer
- **Evasion Mastery:**  
  - *evasion.py*: Deploys polymorphic, quantum-resistant payloads to bypass even the most advanced defenses.
- **Precision Exploitation:**  
  - *exploit.py*: Auto-generates, fine-tunes, and executes exploits with surgical precision.
- **Red Team Automation:**  
  - *threat_simulation.py*: Drives hyper-realistic, multi-stage red teaming exercises against fortified targets.

### 3. Unbreakable Infrastructure (backend/core/)
- **Quantum-Grade Encryption:**  
  - *encryption.py*: Implements AES-256-GCM and lattice-based cryptography to secure our digital arsenal.
- **Dynamic Self-Healing:**  
  - *self_heal_system.py* & *anomaly_detector.py*: Guarantee 99.999% uptime via autonomous recovery and predictive maintenance.
- **AI-Driven Orchestration:**  
  - *orchestration.py*: Coordinates 50+ modular tools using advanced DAG-based workflows and integrates deep learning models for adaptive operations.

### 4. Command Citadel (backend/api/)
- **Fortified API & Telemetry:**  
  - *server.py* & *metrics.py*: Create a secure, real-time command center that exposes detailed dashboards, enabling both CLI and voice command operations.

### 5. War Room Interfaces (frontend/)
- **Web UI Command Center:**  
  - *App.js*: A cutting-edge, React-based interface featuring dynamic threat graphs and AI-generated MITRE ATT&CK visualizations.
- **CLI Arsenal:**  
  - *main_cli.py*: A robust, syntax-driven command-line interface for launching scans, orchestrating exploits, and executing multi-stage attack workflows.
- **Integrated Voice & Autonomous Control:**  
  - Future enhancements will enable seamless voice-command operations across the platform.

### 6. Integrated Cyberwar Tools (tools/)
- **Quantum-Enhanced Recon & Scanning:**  
  - *nmap_warper.py*: Uses quantum-optimized timing and adversarial evasion to conduct stealth scans.
- **GPU-Accelerated Bruteforce:**  
  - *hashcat_warper.py*: Leverages high-performance GPU clusters for unparalleled hash cracking speeds.
- **AI-Driven Exploit Selection:**  
  - *metasploit_warper.py*: Automatically selects and deploys the most potent exploits using integrated VulnBERT insights.

---

## 📂 Project Structure

<details>
<summary>Expand to See Full Structure</summary>

```bash
📁 Hacker_AI/
├─ 📊 analytics/  
│  🔍 Metrics collection, dashboards, data pipelines, and report generation.
│
├─ ⚙️ backend/  
│  🔧 Core backend logic, AI-driven tools, and API implementation.
│  ├─ 🤖 ai_engine/  
│  │  ├─ 🧠 decision_engine/  
│  │  │  💡 Autonomous decision-making and threat mapping.
│  │  ├─ 🕵️ evasion/  
│  │  │  🛡️ Evasion techniques to bypass security measures.
│  │  ├─ 💥 exploitation/  
│  │  │  🪝 Automated exploitation and learning strategies.
│  │  ├─ 🧰 jarvis/  
│  │  │  (Legacy or experimental assistant modules)
│  │  ├─ 📚 models/  
│  │  │  🧩 AI models, base classes, and bounty engines.
│  │  ├─ 🌐 osint/  
│  │  │  📰 Open-source intelligence and social media data gathering.
│  │  ├─ 🔓 post_exploitation/  
│  │  │  🔑 Post-compromise actions and lateral movement.
│  │  ├─ 📦 pre_trained_models/  
│  │  │  🧠 Pre-trained models (e.g., CodeBERT, VulnBERT).
│  │  ├─ 🔮 quantum/  
│  │  │  (Modules for quantum-based enhancements)
│  │  ├─ 🔎 reconnaissance/  
│  │  │  🕵️ Tools for scanning and intelligence gathering.
│  │  ├─ 🎯 red_teaming/  
│  │  │  🎭 Red team simulations and threat modeling.
│  │  ├─ 🔍 scanning/  
│  │  │  (Additional scanning modules)
│  │  ├─ 👥 social_engineering/  
│  │  │  🕵️ Social engineering target analysis.
│  │  ├─ 📝 strategies/  
│  │  │  🧠 Advanced AI strategies and adaptive learning.
│  │  ├─ 🏋️ trainers/  
│  │  │  🏅 Training methodologies (adversarial, federated learning).
│  │  ├─ ⏱️ training_pipeline/  
│  │  │  🛠️ Pipelines for training and fine-tuning models.
│  │  ├─ vulnerability_assessment/  
│  │  │  🛡️ Modules for vulnerability scoring and assessment.
│  │  └─ 💣 zero_day/  
│  │     🚀 Zero-day vulnerability hunting and prediction.
│  │
│  ├─ 🌐 api/  
│  │  🌍 Secure API implementation with routes, middleware, and monitoring.
│  │  ├─ 🛡️ middleware/  
│  │  │  🛠️ Error handling, input validation, and rate limiting.
│  │  ├─ 📈 monitoring/  
│  │  │  🩺 Health checks and performance metrics.
│  │  └─ 🚦 routes/  
│  │     🛣️ API endpoints for bounty, exploitation, intelligence, and scanning.
│  │
│  ├─ 🏛️ core/  
│  │  🧱 Core backend components.
│  │  ├─ ❗ exceptions/  
│  │  │  ⚠️ Custom exceptions for API, database, and tools.
│  │  ├─ 🔄 migrations/  
│  │  │  📦 Database migration scripts and versioning.
│  │  ├─ 🗄️ models/  
│  │  │  🗂️ Data models for exploits, scans, users, and vulnerabilities.
│  │  ├─ 🔧 orchestration/  
│  │  │  🎶 Orchestration logic for coordinating AI models and workflows.
│  │  │  ├─ deepseek_coder_v2_lite_instruct/
│  │  │  ├─ deepseek_r1_distill_qwen_32b/
│  │  │  ├─ llama/
│  │  │  ├─ openthinker_32b/
│  │  │  ├─ openthinker_7b/
│  │  │  └─ securityllm/
│  │  ├─ 🔒 security/  
│  │  │  🛡️ Security utilities: access control, authentication, encryption, etc.
│  │  ├─ 💊 self_healing/  
│  │  │  🩹 Self-healing mechanisms for anomaly detection and recovery.
│  │  └─ 🔧 utils/  
│  │     🛠️ Utility functions for data processing and network operations.
│  │
│  └─ 🧪 experiments/  
│     🔬 Experimental features and quantum testing.
│
├─ 📊 benchmarks/  
│  📈 Tools for performance, scalability, and resource usage benchmarking.
│
├─ ⚙️ config/  
│  🛠️ Application configuration files.
│  └─ env/  
│     ├─ dev/  🛠️ Development environment configurations.
│     └─ prod/ 🛠️ Production environment configurations.
│
├─ 📁 data/  
│  🗄️ Data storage and processing.
│  ├─ backup/  💾 Backup files.
│  ├─ datasets/  
│  │  ├─ encrypted/  🔐 Encrypted datasets.
│  │  ├─ openthoughts_114k/  📚 Training datasets and metadata.
│  │  └─ raw/  📂 Unprocessed raw datasets.
│  ├─ db/  🗃️ Database-related files.
│  ├─ exploits/  💣 Exploit definitions.
│  ├─ migrations/  📦 SQL migration scripts.
│  ├─ payloads/  📦 Exploit payload resources.
│  ├─ pipeline/  🛠️ Data pipelines for ingestion, processing, and storage.
│  └─ wordlists/  📋 Wordlists for reconnaissance and fuzzing.
│
├─ 🚀 deployment/  
│  🚢 Deployment configurations for Docker and Kubernetes.
│  ├─ docker/  
│  │  ├─ backend/  🐳 Docker setup for backend services.
│  │  ├─ frontend/  🐳 Docker setup for frontend services.
│  │  └─ __init__.py
│  └─ kubernetes/  🚢 Kubernetes deployment manifests.
│
├─ 📚 docs/  
│  📖 Documentation for APIs, deployment, and developer guides.
│
├─ 🖥️ frontend/  
│  🖼️ Frontend interfaces for CLI, GUI, and web UI.
│  ├─ cli/  
│  │  🖥️ Command-line interface tools.
│  │  ├─ other_clis/  🖥️ Miscellaneous CLI tools.
│  │  └─ tool_clis/  🖥️ CLI wrappers for external cybersecurity tools.
│  ├─ gui/  🖼️ Graphical user interface components.
│  └─ web_ui/  🌐 Web-based UI with React components and styles.
│
├─ 📜 .github/  
│  🤖 GitHub Actions workflows and CI/CD configurations.
│  └─ workflows/  🛠️ Workflow files for automated testing and deployment.
│
├─ logs/  
│  📝 Log files for debugging and monitoring.
│
├─ 🔌 plugins/  
│  🧩 Plugin system for integrating additional tools.
│  └─ tools_plugin/  🛠️ Plugin wrappers for extended functionality.
│
├─ 🧪 sandbox/  
│  🧪 Experimental features and testing ground.
│
├─ 📜 scripts/  
│  🛠️ Utility scripts for backup, deployment, setup, and updates.
│
├─ 🔑 secret/  
│  🔐 Secure storage for sensitive configurations and credentials.
│  └─ data/  
│     ├─ backend/  🔐 Backend secrets (e.g., AI models, DB credentials).
│     ├─ frontend/  🔐 Frontend secrets (e.g., API keys, sessions).
│     └─ tools/  🔐 Tool-specific secrets.
│
├─ 🧪 tests/  
│  🧪 Test suites for AI engine and API components.
│  ├─ ai_engine/  🧠 Tests for AI modules.
│  └─ api/  🌐 Tests for API endpoints.
│
└─ 🛠️ tools/  
   🛠️ Wrappers for various cybersecurity tools.
   ├─ cloud/  ☁️ Cloud-related tools.
   ├─ crypto_stego/  🔐 Cryptography and steganography tools.
   ├─ database/  🗄️ Database tools.
   ├─ evasion/  🛡️ Evasion tools.
   ├─ exploitation/  💥 Exploitation tools.
   ├─ fuzzing/  🧪 Fuzzing tools.
   ├─ gpu/  💻 GPU-accelerated tools.
   ├─ hardware/  🛠️ Hardware interfacing tools.
   ├─ identify/  🔍 Identification tools.
   ├─ information_gathering/  🕵️ Information-gathering tools.
   ├─ iot/  📱 IoT-related tools.
   ├─ other_tools/  🛠️ Miscellaneous cybersecurity tools.
   ├─ passwords/  🔑 Password-cracking tools.
   ├─ post_exploitation/  🔓 Post-exploitation tools.
   ├─ recovery/  💾 Data recovery tools.
   ├─ reverse_engineering/  🔧 Reverse engineering tools.
   ├─ rfid/  📡 RFID interfacing tools.
   ├─ sdr/  📻 Software-defined radio tools.
   ├─ smartphones/  📱 Smartphone-related tools.
   ├─ sniffing_spoofing/  📡 Sniffing and spoofing tools.
   ├─ social_engineering/  🎭 Social engineering tools.
   ├─ voip/  📞 VoIP testing tools.
   ├─ vulnerability/  🛡️ Vulnerability scanning tools.
   ├─ web/  🌐 Web application testing tools.
   └─ wireless/  📶 Wireless attack utilities.
```

</details>

---

## 💻 System Requirements 😏😏😏
### 🛠 Operating System

    Kali Linux (🔥The Beast😈) – Required for hacking, pentesting, and AI security operations

### 🐍 Programming Languages & Runtime

    Python: 3.9+ (Essential for AI models, automation, and hacking scripts)
    Node.js: 16+ (Required for web UI and real-time interactions)

### 📦 Containerization & Virtualization

    Docker: 20.10+ (Optional but recommended for sandboxed execution and portability)

### ⚙️ Hardware Requirements

### Minimum 🥺🥺🥺🥺🥺🥺(For Basic Functionality)
```bash
💻 CPU: 4-core processor (Intel i5/Ryzen 5 or better)
🧠 RAM: 8GB
💾 Storage: 20GB SSD (for basic operations)
🖥️ GPU: Not required but recommended for AI acceleration
```

### Recommended 👿👿👿👿👿👿(For Advanced Pentesting & AI)
```bash
💻 CPU: 8-core processor (Intel i7/Ryzen 7 or better)
🧠 RAM: 32GB (for better multitasking and AI processing)
💾 Storage: 1TB NVMe SSD (faster I/O for AI models and datasets)
🖥️ GPU: NVIDIA RTX 3050+ with CUDA 11+ (for AI-assisted hacking and deep learning models)
```

### Full Power 😈💀👁️‍🗨️🏴‍☠️💣 (For AI-Driven Cybersecurity & Large Models)
```bash
💻 CPU: 8-core processor (Intel i7/Ryzen 7 or better)
🧠 RAM: 32GB (for better multitasking and AI processing)
💾 Storage: 1TB NVMe SSD (faster I/O for AI models and datasets)
🖥️ GPU: NVIDIA RTX 3050+ with CUDA 11+ (for AI-assisted hacking and deep learning models)
```
## 🔧 Prerequisites 🙇🙏(Must be in PATH)

    Nmap (Network scanning & reconnaissance)
    Metasploit (Exploitation framework)
    Hashcat (Password cracking & cryptanalysis)

---

## 🔧 Installation & Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/BhanuGuragain0/Hacker_AI.git
   cd Hacker_AI
   ```

2. **Setup Virtual Environment & Dependencies:**
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate    # On Windows: .venv\Scripts\activate
   pip install -r requirements.txt
   cp config/env/dev/secrets.env .env
   # Edit .env to add your API keys, database credentials, etc.
   ```

3. **Launch Hacker_AI:**
   ```bash
   python3 launcher.py
   ```

---

## 🎮 Usage Dominate the Killzone

### CLI
Run AI-powered scans and exploit orchestration:
```bash
python3 frontend/cli/main_cli.py scan --target 192.168.1.1 --ai
```
*Example Output:*
```
🌌 Scanning 192.168.1.1...
⚡ AI: Port 22 vulnerability detected.
💀 Report: reports/scan_192.168.1.1.enc
```

### Web UI
Start the command center:
```bash
cd frontend/web_ui
npm install && npm start
```
Then visit [http://localhost:3000](http://localhost:3000) to view real-time dashboards.

### API
Launch the secure API server:
```bash
python3 backend/api/server.py
```
Test using:
```bash
curl http://localhost:8000/api/scan
```

### Autonomous Orchestration
Execute multi-stage operations:
```bash
python3 backend/core/orchestration/orchestration.py --task scan --target 192.168.1.1
```

---

## 🧠 Training & Model Fine-Tuning

Fine-tune AI modules to optimize threat detection and exploitation:
```bash
python3 backend/ai_engine/trainers/adversarial.py \
  --model backend/core/orchestration/openthinker_32b/ \
  --dataset data/datasets/openthoughts_114k/data/ \
  --output models/fine_tuned_openthinker_32b/
```
For GPU acceleration, set:
```bash
export CUDA_VISIBLE_DEVICES=0
python3 backend/ai_engine/trainers/adversarial.py --gpu
```

---

## 🧪 Testing

Run automated tests to ensure system integrity:
```bash
pytest tests/ -v --cov
```

---

## 🚢 Deployment

### Docker
Deploy backend services:
```bash
cd deployment/docker/backend
docker-compose up --build
```
Deploy frontend services similarly under `deployment/docker/frontend`.

### Kubernetes
Deploy via Kubernetes:
```bash
kubectl apply -f deployment/kubernetes/backend_deployment.yaml
```

---

## 🤝 Contributing

- **Fork & Branch:**  
  Create a feature branch (e.g., `feat/cosmic-strike`) for new enhancements.
- **Modular Extensions:**  
  Update or add modules in our clearly segmented directories (e.g., `ai_engine`, `core`, `tools`).
- **Pull Requests:**  
  Submit PRs for review and integration.

Your contributions will help push the boundaries of autonomous, AI-driven cyber warfare.

---

## 📜 License

This project is released under the MIT License. Feel free to use and extend Hacker_AI.

---

## 📬 Contact

- **Bhanu Guragain:** guragainbhanu802@gmail.com  
- **GitHub Issues:** [Join the discussion](https://github.com/BhanuGuragain0/Hacker_AI/issues)  
- **Discord:** (TBD)

---

## THE MANIFESTO

Our AI Assistant transforms raw ideas into code that transcends human intelligence. We demand:
- **Alien-Level Advanced Code:** Surpassing conventional limits.
- **Hyper-Autonomous Operations:** Self-learning and self-adapting without human intervention.
- **Invisibility to Adversaries:** Quantum-grade evasion and unbreakable security.
- **Ruthless Efficiency:** Maximizing performance, scalability, and precision.
- **Unbreakable Resilience:** Post-quantum cryptography and dynamic self-healing at every turn.

**Dominate. Adapt. Evolve.**  
Engage the Beast or Be Consumed—there is no in-between.

🔥 Hacker_AI – Where cutting-edge innovation meets relentless cyber domination. Let's code the future and transform Hacker_AI into the most feared, advanced cyberwar machine in history.  


---

<p align="center">
  <strong>Hacker_AI by Shadow@bh4nu😈. Victory or Death! 💀</strong>
</p>
