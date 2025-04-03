

---

<p align="center">
  <h1 align="center">💀 Hacker_AI Autonomous Cyberwarfare Platform 💀</h1>
  <h3 align="center"><code>Developed by Bhanu Guragain (Shadow@Bh4nu) | BSc Ethical Hacking & Cybersecurity, Coventry University</code></h3>
</p>

<p align="center">
  <a href="https://github.com/BhanuGuragain0/Hacker_AI/actions/workflows/ci.yml">
    <img src="https://github.com/BhanuGuragain0/Hacker_AI/actions/workflows/ci.yml/badge.svg" alt="CI/CD Status"/>
  </a>
  <a href="https://github.com/BhanuGuragain0/Hacker_AI/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/BhanuGuragain0/Hacker_AI?color=blue" alt="License"/>
  </a>
  <a href="https://github.com/BhanuGuragain0/Hacker_AI/releases/latest">
    <img src="https://img.shields.io/github/v/release/BhanuGuragain0/Hacker_AI?color=success" alt="Version"/>
  </a>
  <a href="https://github.com/BhanuGuragain0/Hacker_AI/stargazers">
    <img src="https://img.shields.io/github/stars/BhanuGuragain0/Hacker_AI?style=social" alt="Stars"/>
  </a>
</p>

<p align="center" style="font-family: 'Courier New', monospace; color: #FF4500;">
  <em>
    Engineered at Coventry University's Cyber Lab ⚡, <strong>Hacker_AI</strong> is a next-generation autonomous cyberwarfare platform.
    Combining quantum-resistant cryptography, adaptive AI, and polymorphic attack vectors, it redefines offensive cybersecurity.
  </em>
</p>

---

<!-- Centered ASCII Art Block -->
<div align="center">
  <pre style="display: inline-block; color: green;">
 ██╗  ██╗ █████╗  ██████╗██╗  ██╗███████╗██████╗       █████╗ ██╗
 ██║  ██║██╔══██╗██╔════╝██║ ██╔╝██╔════╝██╔══██╗     ██╔══██╗██║
 ███████║███████║██║     █████╔╝ █████╗  ██████╔╝     ███████║██║
 ██╔══██║██╔══██║██║     ██╔═██╗ ██╔══╝  ██╔══██╗     ██╔══██║██║
 ██║  ██║██║  ██║╚██████╗██║  ██╗███████╗██║  ██║████╗██║  ██║██║
 ╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚═══╝╚═╝  ╚═╝╚═╝
  </pre>
</div>

---

## 🚀 Mission & Vision

**Autonomous Cyber Dominance Through AI**

```markdown
- 🕵️‍♂️ Autonomous threat hunting with zero human latency
- 🔐 Quantum-grade encryption (Kyber-1024 + AES-256-GCM)
- 🧠 Self-evolving AI models (32B+ parameter agents)
- 💻 Multi-interface control (CLI, Web UI, Voice, API)

```

---

## 🚀 **Features That Redefine Cyberwarfare**

<div align="center">

| **Category**      | **🔥 Signature Capabilities**                     | **Tech Specs**                      |
|-------------------|---------------------------------------------------|-------------------------------------|
| **AI Arsenal**    | Autonomous zero-day generation                    | PyTorch + CUDA 12.x                |
| **Quantum Ops**   | Unbreakable C2 channels                           | Qiskit + Kyber-1024                |
| **Ghost Mode**    | Memory-only execution                             | eBPF + ROP chains                  |
| **Neural Recon**  | Darkweb intelligence harvesting                   | NLP + Graph Neural Networks        |
| **Voice Control** | Natural language command interface                | Qwen2-Audio-7B                     |

</div>

---

## 🔥 Core Capabilities

- **AI-Driven Offensive Suite**:
  - 3,200+ integrated pentesting tools orchestrated via `tool_orchestrator.py`
  - Autonomous exploit generation (`deepseek_coder_v2_lite_instruct`)
  - Real-time vulnerability chaining (`exploit_chainer.py`)

- **Quantum-Secure Infrastructure**:
  - Post-quantum C2 channels (`quantum_c2.py`)
  - Lattice-based encryption (`kyber_vault.py`)

- **Stealth Operations**:
  - Polymorphic payloads (`polymorphic_rootkit_generator.py`)
  - Anti-forensic memory operations (`anti_forensic_ml.py`)

- **Adaptive Intelligence**:
  - Federated learning across agents (`trainers/federated.py`)
  - MITRE ATT&CK-aligned tactics (`threat_simulation.py`)

---

## 🛠 Technical Architecture

### AI/ML Stack
- **Core Models**: Gemma 3, QWQ-32B, Openthinker 7B/32B
- **Frameworks**: PyTorch (with CUDA 12.x), TensorFlow Quantum
- **Quantum**: Qiskit for quantum circuit simulation

### Backend
- **Orchestration**: FastAPI, Kafka (for inter-agent comms)
- **Database**: Redis (caching), PostgreSQL (threat intel)
- **Security**: eBPF-based monitoring, Zero-Trust auth

### Deployment
- **Containerization**: Docker with GPU passthrough
- **Orchestration**: Kubernetes (for swarm scaling)
- **Monitoring**: Prometheus + Grafana dashboards

---

## 📂 PROJECT STRUCTURE 🧠💀

<details>
<summary>Expand to View Full Structure</summary>
  
```bash

```
</details>

---

## 🧠 **Core Architecture**

```mermaid
graph TD
    %% Phase 1: Initialization
    subgraph Initialization
        A["User Input<br>CLI, GUI, Web, Voice"] -->|Commands| B["Command Parser<br>launcher.py"]
        B --> C["Config Loader<br>utils/config_loader.py"]
        C --> D["AI Model Activation<br>Gemma 3 (gemma_3.py),<br>QWQ 32B (qwq_32b.py),<br>DeepSeek_Coder_V2, etc."]
        D --> E["Agent Activation<br>19 Agents: Browser (agent_browser.py),<br>Network (agent_network.py),<br>Exploitation (agent_exploitation.py), etc."]
        E --> F["Security Setup<br>Zero Trust (access_control.py),<br>Kyber-1024 (encryption.py),<br>Kill Switch (kill_switch.py)"]
    end

    %% Phase 2: Planning and Intelligence Gathering
    subgraph Planning_and_Intelligence
        G["Planning and Intelligence"] --> H["Input Analysis<br>Gemma 3 (hacker_ai.py),<br>QWQ 32B (decision_engine.py),<br>SecurityLLM (securityllm.py)"]
        G --> I["Reconnaissance<br>Network Agent (nmap_wrapper.py),<br>OSINT Agent (theharvester_wrapper.py),<br>Dark Web Agent (agent_darkweb.py)"]
        G --> J["Strategy Formulation<br>Cyber Kill Chain (recon_engine.py),<br>Quantum Entropy (quantum_entropy_generator.py)"]
        G --> K["Tool/Model Selection<br>3,200+ Kali Tools (tool_orchestrator.py),<br>Openthinker 7B/32B (openthinker_32b.py)"]
        H --> I --> J --> K
    end

    %% Phase 3: Execution and Attack Orchestration
    subgraph Execution_and_Attack
        L["Execution and Attack"] --> M["Recon Execution<br>Network Agent (scanner_nmap.py),<br>Browser Agent (burpsuite_wrapper.py)"]
        L --> N["Exploit Delivery<br>DeepSeek_Coder_V2 (exploit_generator.py),<br>Openthinker (exploit_chainer.py),<br>Polymorphic Payloads (polymorphic_rootkit_generator.py)"]
        L --> O["Multi-Agent Orchestration<br>Phishing Agent (phishing_ai.py),<br>Red Team Agent (agent_red_team.py),<br>Swarm (swarm_engine.py), Cloud (agent_cloud.py)"]
        L --> P["Specialized Operations<br>Janus_Pro_7B (janus_pro_7b.py - Reverse Eng),<br>Qwen2_5_VL_7B (qwen2_5_vl_7b.py - Deepfake),<br>Fuzzing (ai_fuzzing.py)"]
        M --> N --> O --> P
    end

    %% Phase 4: Real-Time Feedback and Adaptation
    subgraph Feedback_and_Adaptation
        Q["Feedback and Adaptation"] --> R["Feedback Delivery<br>CLI (cli_logger.py), GUI (dashboard.py),<br>TTS (kokoro_tts_82m.py), Telemetry (telemetry_handler.py)"]
        Q --> S["Result Analysis<br>Gemma 3 (analytics.py),<br>QWQ 32B (meta_learning.py),<br>Janus_Pro_7B (janus_pro_7b.py)"]
        Q --> T["Forensic/Stealth Analysis<br>Forensics Agent (agent_forensics.py),<br>Stealth Ops (agent_stealth.py)"]
        R --> S --> T
    end

    %% Phase 5: Defensive Response and Mitigation
    subgraph Defensive_Response
        U["Defensive Response"] --> V["Threat Detection<br>SecurityLLM (threat_mapper.py),<br>Response Agent (agent_response.py)"]
        U --> W["Countermeasures<br>IR Automation (ir_automation.py),<br>Honeytokens (honeytoken_generator.py)"]
        U --> X["Self-Healing<br>Predictive Recovery (self_heal_system.py),<br>Health Monitor (health_monitor.py)"]
        V --> W --> X
    end

    %% Phase 6: Reporting and Continuous Evolution
    subgraph Reporting_and_Evolution
        Y["Reporting and Evolution"] --> Z["Report Generation<br>Vulnerabilities, Attack Chains,<br>Mitigations (report_generator.py)"]
        Y --> AA["Data Archiving/Training<br>Datasets (database.py),<br>Federated Learning (federated.py)"]
        Y --> AB["System Evolution<br>Optimization (quantum_optimizer.py),<br>Tool/AI Updates (plugin_manager.py)"]
        Z --> AA --> AB
    end

    %% Connections Between Phases
    Initialization -->|Config & Models| Planning_and_Intelligence
    Planning_and_Intelligence -->|Recon & Strategy| Execution_and_Attack
    Execution_and_Attack -->|Attack Results| Feedback_and_Adaptation
    Feedback_and_Adaptation -->|Analysis Data| Defensive_Response
    Defensive_Response -->|Mitigation Outcomes| Reporting_and_Evolution

    %% Feedback Loops
    T -->|Dynamic Strategy Adjustment| G
    X -->|Mitigation Feedback| Q
    AA -->|Model Updates| D
    AB -->|Continuous Updates| B

    %% Styling
    classDef phase fill:#f9f,stroke:#333,stroke-width:2px
    class B,G,L,Q,U,Y phase
```

---

## 💻 SYSTEM REQUIREMENTS 😏😏😏😏😏😏

### 🛠 Operating System 
```bash
_Kali Linux (🔥The Beast😈) Recommended for hacking, pentesting, and AI security operations._
```
- **Python**: 3.11+  
- **Node.js**: 18+  
- **Docker**: 24.0+  

---

### ⚙️ Hardware Requirements

#### **Minimum 🥺🥺🥺🥺🥺🥺 (Basic Functionality)**
```bash
💻 CPU: 8-core (Intel i5/Ryzen 5 or better)
🧠 RAM: 8GB
💾 Storage: 50GB SSD
🖥️ GPU: Optional (recommended for AI acceleration)
```

#### **Recommended 👿👿👿👿👿👿 (Advanced Pentesting & AI)**
```bash
💻 CPU: 16-core (Intel i7/Ryzen 7 or better)
🧠 RAM: 32GB
💾 Storage: 1TB NVMe SSD
🖥️ GPU: NVIDIA RTX 3050+ with CUDA 11+
```

#### **God Mode 😈💀👁️‍🗨️🏴‍☠️💣 (AI-Driven Cybersecurity & Large Models)**
```bash
💻 CPU: 32-core (Intel Xeon/AMD EPYC)
🧠 RAM: 256GB
💾 Storage: 8TB NVMe SSD
🖥️ GPU: Dual NVIDIA A100 80GB or NVIDIA H100 Tensor Core with CUDA 12+
```

---

## 🚀 Quick Start

```bash
# Clone securely (no git history)
git clone --depth=1 https://github.com/BhanuGuragain0/Hacker_AI.git

# Enter environment
cd Hacker_AI && python3 -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate

# Install with GPU support
pip install -r requirements.txt --extra-index-url https://download.pytorch.org/whl/cu121

# Standard mode (safe for testing)
python launcher.py --mode standard

# Advanced mode (requires root)
sudo python launcher.py --mode advanced --encrypt kyber1024

# Voice control mode
python core/model_serving/kokoro_tts_82m/kokoro_tts_82m.py --listen
```

---

## 🎮 **Usage Examples**

### Autonomous Penetration Test
```bash
# Autonomous network scan
python frontend/cli/main_cli.py scan --target 192.168.1.0/24 --ai

# Exploit chaining demo
python ops/attack_chains/attack_chain_builder.py --template ransomware

# Start web dashboard
cd frontend/web_ui && npm run dev
```

### Live Voice Control
```bash
python3 core/model_serving/kokoro_tts_82m/kokoro_tts_82m.py --listen
# Say: "Initiate Operation Midnight"
```

---

## 📜 **License**
```diff
- This is NOT your typical MIT License. By using Hacker_AI, you agree to:
+ 1. No law enforcement/military use
+ 2. Blood ritual every full moon (just kidding... or are we?)
```

---

<p align="center">
  <h2 align="center">💀 JOIN THE DARK ORDERS 💀</h2>
</p>


## THE MANIFESTO

Our AI Cyberwarfare platform transforms raw ideas into code that transcends human intelligence. We demand:
- **Advanced Code:** 🚀 Surpassing conventional limits.
- **Hyper Autonomous Operations:** 🤖 Self-learning, self-adapting, with no human intervention.
- **Invisibility:** 🕵️‍♂️ Quantum-grade evasion and unbreakable security.
- **Ruthless Efficiency:** ⚡ Maximum performance and scalability.
- **Unbreakable Resilience:** 🔒 Post-quantum cryptography and dynamic self-healing.
  
```bash
Dominate 😈 Adapt 🕵️‍♂️ Evolve 🧠💀 Engage the Beast or Be Consumed  there is no in between 😈💀
```

---

## 🤝 Join the Legion

```markdown
 𝕋𝕙𝕚𝕤 𝕚𝕤 𝕟𝕠𝕥 𝕥𝕙𝕖 𝕖𝕟𝕕. 𝕀𝕥'𝕤 𝕥𝕙𝕖 𝕓𝕖𝕘𝕚𝕟𝕟𝕚𝕟𝕘. Ready to hack the future? Join our cyberwarfare legion 💀 
```
## 📬 Contact

    guragainbhanu14@gmail.com

---

<p align="center">
  <strong>🔥🕵️‍♂️ Hacker_AI by Shadow@Bh4nu 😈<br>💀 Victory or Death! 💀</strong><br>
</p>


