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
  <em>Born in Coventry University’s chaos forge, **Hacker_AI** is a JARVIS-grade platform—AI autonomy, stealth tactics, and self-healing resilience fused to dominate the digital battlefield.</em>
</p>

---
```markdown
## 🌐 What is Hacker_AI?

**Hacker_AI** is an AI-powered cybersecurity juggernaut built to outsmart elite threats. It hunts zero-days with `zero_day_hunter.py`, orchestrates
precision strikes via `orchestration.py`, and leverages fine-tuned models like `deepseek_coder_v2_lite_instruct/` and `openthinker_32b/`. Crafted by a
student and an AI beast, it’s the ultimate weapon for pentesters, researchers, and defenders.

> **Our Edge**: Bhanu Guragain (Shadow Junior) and Shadow Senior—academic grit meets AI muscle to crush tomorrow’s threats.



## ✨ Killer Features

| Feature                   | Why It Roars                                                         | Dive In                                  |
|---------------------------|----------------------------------------------------------------------|------------------------------------------|
| **AI-Powered Offense**    | Autonomous exploits with `codebert_base.pt` and `deepseek_coder_v2`. | `backend/ai_engine/exploitation/`        |
| **Zero-Day Hunting**      | ML-driven threat prediction with real-time edge.                     | `backend/ai_engine/zero_day/`            |
| **Self-Healing Core**     | Anomaly detection (`xgboost`) and auto-recovery under fire.          | `backend/core/self_healing/`             |
| **Tool Arsenal**          | 30+ wrappers—Nmap, Metasploit, Hashcat, and more.                    | `tools/`                                 |
| **Orchestration Mastery** | Fine-tuned models (`openthinker_32b`) coordinate chaos.              | `backend/core/orchestration/`            |
| **Quantum-Safe Crypto**   | Future-proof encryption for tomorrow’s wars.                         | `backend/core/security/encryption.py`    |
| **Scalable Power**        | Dockerized and Kubernetes-ready—deploy anywhere.                     | `deployment/`                            |
| **Plugin Freedom**        | Extend with your own chaos.                                          | `plugins/`                               |

```
---

## 📂 Project Structure

A 115-directory, 418-file titan powering the cybersecurity revolution. Here’s the core:

```bash
Hacker_AI/
├── analytics/                          # Metrics and visualization
│   ├── dashboard.py                   # Real-time analytics UI
│   ├── metrics_collector.py           # System/AI metrics
│   └── report_generator.py            # Detailed reports
├── backend/                            # AI, API, and core logic
│   ├── ai_engine/                     # AI-driven hacking core
│   │   ├── decision_engine/           # Threat decisions
│   │   │   ├── ai_decision.py         # Predictive logic
│   │   │   └── threat_mapper.py       # Threat prioritization
│   │   ├── evasion/                   # Stealth tactics
│   │   │   └── evasion.py             # Evasion strategies
│   │   ├── exploitation/              # Exploit automation
│   │   │   ├── exploit.py             # Exploit execution
│   │   │   └── auto_learning.py       # Adaptive exploits
│   │   ├── models/                    # AI model definitions
│   │   │   ├── base_model.py          # Base model class
│   │   │   └── code_analyzer.py       # Code vuln analysis
│   │   ├── osint/                     # Open-source intel
│   │   │   └── osint_engine.py        # OSINT gathering
│   │   ├── post_exploitation/         # Post-exploit ops
│   │   │   └── post_exploit.py        # Post-exploit logic
│   │   ├── pre_trained_models/        # Pre-trained AI firepower
│   │   │   ├── codebert_base.pt       # Code vuln analysis
│   │   │   ├── vulnbert_base.pt       # Vuln prediction
│   │   │   └── vulnerability_predictor.pt # General vuln predictor
│   │   ├── reconnaissance/            # Target recon
│   │   │   └── recon_engine.py        # AI-enhanced scanning
│   │   ├── red_teaming/               # Adversarial simulations
│   │   │   └── threat_simulation.py   # APT simulations
│   │   ├── scanning/                  # Scanning ops (placeholder)
│   │   ├── strategies/                # Advanced AI strategies
│   │   │   ├── hyperdimensional.py    # Hyperdimensional computing
│   │   │   └── neuroplasticity.py     # Adaptive learning
│   │   ├── trainers/                  # Model training
│   │   │   ├── adversarial.py         # Adversarial training
│   │   │   └── federated.py           # Federated learning
│   │   ├── training_pipeline/         # Tool-integrated training
│   │   │   ├── nmap_pipeline.py       # Nmap training
│   │   │   └── sqlmap_pipeline.py     # SQLmap training
│   │   ├── vulnerability_assessment/  # Vuln analysis (placeholder)
│   │   └── zero_day/                  # Zero-day discovery
│   │       ├── predictor.py           # Zero-day prediction
│   │       └── zero_day_hunter.py     # Novel threat hunter
│   ├── api/                           # RESTful command hub
│   │   ├── auth.py                    # Authentication logic
│   │   ├── server.py                  # API backbone
│   │   ├── middleware/                # Request hardening
│   │   │   ├── error_handler.py       # Error handling
│   │   │   ├── input_validation.py    # Input sanitization
│   │   │   └── rate_limiter.py        # Rate limiting
│   │   ├── monitoring/                # Health tracking
│   │   │   ├── health.py              # Health checks
│   │   │   └── metrics.py             # Live metrics
│   │   └── routes/                    # API endpoints
│   │       ├── bounty.py              # Bug bounty services
│   │       ├── exploit.py             # Exploit services
│   │       ├── intelligence.py        # Threat intel
│   │       └── scan.py                # Scan services
│   ├── core/                          # Foundational beast
│   │   ├── architecture.py            # System design
│   │   ├── exceptions/                # Custom exceptions
│   │   │   ├── api_exceptions.py      # API errors
│   │   │   └── tool_exceptions.py     # Tool errors
│   │   ├── migrations/                # DB migrations
│   │   │   └── alembic.ini            # Migration config
│   │   ├── models/                    # Data models
│   │   │   ├── exploit_results.py     # Exploit results
│   │   │   └── scan_results.py        # Scan results
│   │   ├── orchestration/             # Workflow mastery
│   │   │   ├── deepseek_coder_v2_lite_instruct/ # Coding AI
│   │   │   ├── deepseek_r1_distill_qwen_32b/ # Heavy-duty NLP
│   │   │   ├── exploit_coordinator.py # Exploit flows
│   │   │   ├── llama/                 # LLaMA placeholder
│   │   │   ├── openthinker_32b/       # 32B reasoning model
│   │   │   ├── openthinker_7b/        # 7B reasoning model
│   │   │   ├── orchestration.py       # Task coordination
│   │   │   ├── scan_coordinator.py    # Scan flows
│   │   │   └── securityllm/           # Security-focused LLM
│   │   ├── security/                  # Ironclad defenses
│   │   │   ├── encryption.py          # Quantum-safe crypto
│   │   │   ├── csrf_protection.py     # Web security
│   │   │   └── tools_manager.py       # Tool integration
│   │   ├── self_healing/              # Resilience core
│   │   │   ├── anomaly_detector.py    # ML anomaly detection
│   │   │   └── self_heal_system.py    # Auto-recovery
│   │   └── utils/                     # Helper utils
│   │       └── network.py             # Network utils
│   └── experiments/                    # R&D
│       └── quantum_test.py            # Quantum experiments
├── benchmarks/                         # Performance tests
│   ├── penetration.py                 # Pentest benchmarks
│   └── performance_benchmark.py       # System performance
├── config/                             # Configuration
│   ├── app_config.yaml                # App settings
│   └── tools_config.json              # Tool configs
├── data/                               # Datasets and resources
│   ├── db/                            # Database
│   │   └── database.py                # DB logic
│   ├── exploits/                      # Exploit storage
│   ├── payloads/                      # Payload storage
│   └── wordlists/                     # Brute-force lists
│       ├── big.txt                    # Large wordlist
│       └── subdomains-top1million-110000.txt # Top subdomains
├── deployment/                         # Scalable deployment
│   ├── docker/                        # Containerized power
│   │   ├── backend/                   # Backend Docker
│   │   │   ├── Dockerfile             # Backend image
│   │   │   └── docker-compose.yml     # Backend composition
│   │   └── frontend/                  # Frontend Docker
│   │       └── Dockerfile             # Frontend image
│   └── kubernetes/                    # Cluster-ready
│       └── backend_deployment.yaml    # K8s deployment
├── docs/                               # Documentation
│   ├── api.md                         # API docs
│   └── deployment.md                  # Deployment guide
├── frontend/                           # War room interfaces
│   ├── cli/                           # Command-line power
│   │   ├── main_cli.py                # Main CLI entry
│   │   └── tool_clis/                 # Tool CLIs
│   │       ├── nmap_cli.py            # Nmap wrapper
│   │       └── metasploit_cli.py      # Metasploit wrapper
│   ├── gui/                           # Visual control
│   │   └── dashboard.py               # GUI dashboard
│   └── web_ui/                        # Web command center
│       └── App.js                     # React-based UI
├── logs/                               # Log storage
├── plugins/                            # Extensibility
│   └── tools_plugin/                  # Tool plugin
│       └── plugin.py                  # Plugin logic
├── sandbox/                            # Experiments
│   └── experimental_feature.py        # Test features
├── scripts/                            # Automation
│   ├── deploy.sh                      # Deployment script
│   └── setup.sh                       # Setup script
├── secret/                             # Secrets
│   └── data/                          # Sensitive data
│       ├── backend/                   # Backend secrets
│       │   └── ai_models.json         # Model configs
│       └── tools/                     # Tool secrets
│           └── nmap.json              # Nmap configs
├── tests/                              # Test suites
│   ├── ai_engine/                     # AI tests
│   │   └── test_evasion.py            # Evasion tests
│   └── api/                           # API tests
│       └── test_routes.py             # Route tests
├── tools/                              # Tool wrappers
│   ├── cloud/                         # Cloud tools
│   │   └── aws_warper.py              # AWS integration
│   ├── exploitation/                  # Exploit tools
│   │   └── metasploit_warper.py       # Metasploit integration
│   ├── information_gathering/         # Recon tools
│   │   └── nmap_warper.py             # Nmap integration
│   └── passwords/                     # Cracking tools
│       └── hashcat_warper.py          # Hashcat integration
├── .github/                            # GitHub workflows
│   └── workflows/                     # CI/CD
│       └── ci.yml                     # Continuous integration
├── launcher.py                        # Entry point
├── README.md                          # Project overview
└── requirements.txt                   # Dependencies
```
Full Beast: Dive into the repo for all 418 files!
💻 System Requirements

    OS: Linux (Ubuntu 20.04+ preferred), macOS, Windows (WSL2)
    Python: 3.9+
    Node.js: 16+ (web UI)
    Docker: 20.10+ (optional)
    Hardware:
        Minimum: 8GB RAM, 4-core CPU, 20GB storage
        Recommended: 32GB RAM, NVIDIA GPU (CUDA 11+), 100GB SSD
    Prerequisites: nmap, metasploit-framework, hashcat in PATH.

🛠️ Installation
Quick Start

    Clone the Titan
    bash

git clone https://github.com/BhanuGuragain0/Hacker_AI.git
cd Hacker_AI
Set Up Env
bash
python3 -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
Configure Secrets
bash
cp config/env/dev/secrets.env .env
nano .env  # Add API keys (Shodan, etc.), DB creds
Unleash It
bash

    python launcher.py

Issues? Check logs/app.log or Troubleshooting.
🎮 Usage
<p align="center"> <img src="https://github.com/BhanuGuragain0/Hacker_AI/raw/main/docs/assets/demo.gif" alt="Hacker_AI Demo" width="600"/> </p>
CLI Strike

Scan with AI:
bash
python frontend/cli/main_cli.py scan --target 192.168.1.1 --ai

Output:
text
🔍 Scanning 192.168.1.1...
🤖 AI: Port 22 (SSH) open - Weak auth detected.
🔒 Report: reports/scan_192.168.1.1.enc
Tool Power

Run Nmap:
bash
python frontend/cli/tool_clis/nmap_cli.py -sV 192.168.1.1
GUI Command

Launch dashboard:
bash
python frontend/gui/dashboard.py
Web UI

Serve it:
bash
cd frontend/web_ui
npm install && npm start

Visit http://localhost:3000.
API Hit

Start server:
bash
python backend/api/server.py

Test:
bash
curl http://localhost:8000/api/scan
Orchestrate Chaos

Run orchestrated scan:
bash
python backend/core/orchestration/orchestration.py --task scan --target 192.168.1.1
Train the Beast

Fine-tune openthinker_32b:
bash
python backend/ai_engine/trainers/adversarial.py --model backend/core/orchestration/openthinker_32b/

More: User Guide
⚙️ Configuration

    Env: ENV=dev or ENV=prod in .env.
    Logging: Edit config/logging.yaml.
    Models: Add .safetensors to backend/core/orchestration/.
    Tools: Update config/tools_config.json.

🧪 Testing

Run all:
bash
pytest tests/ -v --cov

    AI: pytest tests/ai_engine/ (90% coverage)
    API: pytest tests/api/ (85% coverage)
    Benchmarks: python benchmarks/performance_benchmark.py

🌐 Deployment
Docker
bash
cd deployment/docker/backend
docker-compose up --build
Kubernetes
bash
kubectl apply -f deployment/kubernetes/backend_deployment.yaml

Guide: Deployment
🤝 Contributing

    Fork it: git checkout -b feat/your-beast-mode
    Hack it: Enhance orchestration.py, add tools/burpsuite_warper.py, or go wild.
    PR it: Join the revolution.

Details: Contributing
🐞 Troubleshooting

    Install Fails: Ensure Python 3.9+, pip install -r requirements.txt --upgrade.
    Tool Errors: Verify nmap, metasploit paths in config/tools_config.json.
    Model Issues: Check GPU/CUDA for openthinker_32b.

Help: Issues
🛤️ Roadmap

    Q2 2025: GPU training for deepseek_* (CUDA 11+).
    Q3 2025: Burp Suite wrapper (tools/web/).
    Q4 2025: Real-time GUI (gui/dashboard.py WebSocket).
    2026: Cloud scale (AWS/Azure in tools/cloud/).

Ideas?: Discussions
🌟 Why Hacker_AI?

    AI Muscle: Fine-tuned openthinker_32b and orchestration.py strike with precision.
    Ethical Core: Student-built to dominate legally.
    Community Power: Open-source, plugin-ready.
    Future-Ready: Quantum-safe, self-healing, adaptive.

📜 License

MIT License—unleash it freely!
📬 Contact

    Bhanu Guragain: guragainbhanu802@gmail.com
    GitHub: Issues
    Discord: Join us! (TBD)

🙏 Acknowledgments

- **Coventry University**: For sparking this journey.
- **Open Source**: nmap, metasploit, pytorch.
- **Shadow@Bh4nu** : Muscle behind the beast.

<p align="center"> <strong>Hacker_AI: Student Grit Meets AI-Powered Domination.</strong> </p>
