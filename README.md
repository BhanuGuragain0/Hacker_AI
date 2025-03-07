
<p align="center">
  <img src="https://via.placeholder.com/200x200.png?text=Hacker_AI" alt="Hacker_AI Logo" width="200"/>
</p>

<h1 align="center">Hacker_AI</h1>

<p align="center">
  <strong>Unleash the Future of Cybersecurity with AI Precision</strong><br>
  Crafted by <a href="https://github.com/BhanuGuragain0">Bhanu Guragain</a>, BSc Ethical Hacking & Cybersecurity, Coventry University
</p>

<p align="center">
  <a href="https://github.com/BhanuGuragain0/Hacker_AI/actions/workflows/ci.yml">
    <img src="https://github.com/BhanuGuragain0/Hacker_AI/actions/workflows/ci.yml/badge.svg" alt="Build Status"/>
  </a>
  <a href="https://github.com/BhanuGuragain0/Hacker_AI/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/BhanuGuragain0/Hacker_AI" alt="License"/>
  </a>
  <a href="https://github.com/BhanuGuragain0/Hacker_AI/releases">
    <img src="https://img.shields.io/badge/version-1.0.0-blue" alt="Version"/>
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
  <em>A student-led revolution in AI-driven ethical hacking—built to outsmart tomorrow’s threats.</em>
</p>

```markdown

## 🌐 What is Hacker_AI?

**Hacker_AI** is an AI-powered cybersecurity toolkit that redefines ethical hacking. Born from my journey as a BSc Ethical Hacking & Cybersecurity student at Coventry University, this project fuses academic insight with real-world grit. It’s not just a tool—it’s a *platform* that leverages advanced AI models, self-healing systems, and 20+ integrated hacking tools to tackle reconnaissance, exploitation, zero-day hunting, and more.

From predicting vulnerabilities with `zero_day_hunter.py` to orchestrating attacks with `exploit_coordinator.py`, Hacker_AI is built for precision, scalability, and adaptability. Whether you’re a pentester, researcher, or defender, this is your edge in an AI-driven world.

> **Why Me?** I’m Bhanu Guragain—a student obsessed with blending theory and practice to push cybersecurity boundaries.


## ✨ Killer Features

| Feature                  | Why It’s Awesome                                      | Dive In                                  |
|--------------------------|-----------------------------------------------------|------------------------------------------|
| **AI-Driven Attacks**     | Precision exploits powered by CodeBERT and VulnBERT. | `backend/ai_engine/exploitation/`       |
| **Zero-Day Prediction**   | Hunt novel threats before they’re known.            | `backend/ai_engine/zero_day/`           |
| **Self-Healing Core**     | Auto-detect and recover from anomalies.             | `backend/core/self_healing/`            |
| **Tool Arsenal**          | Nmap, Metasploit, Hashcat, and 20+ more—unified.    | `tools/`                                |
| **Continuous Evolution**  | Models that learn and adapt in real-time.           | `backend/ai_engine/trainers/`           |
| **Quantum-Ready Crypto**  | Future-proof security for a post-quantum world.     | `backend/core/security/encryption.py`   |
| **Scalable Deployment**   | From laptops to Kubernetes clusters.                | `deployment/`                           |
| **Plugin Extensibility**  | Add your own tools or features effortlessly.        | `plugins/`                              |
```
---

## 📂 Project Structure

Here’s the `Hacker_AI` directory structure 100+ directories, 305+ files powering an AI-driven cybersecurity beast:

```bash
Hacker_AI/
├── analytics/                          # Data analysis and visualization hub
│   ├── dashboard.py                   # Interactive analytics dashboards
│   ├── data_pipeline.py               # Manages data flow and processing
│   ├── metrics_collector.py           # Tracks system and security metrics
│   ├── report_generator.py            # Generates detailed reports
│   └── __init__.py                    # Package initializer
├── backend/                            # Core logic, AI engines, and APIs
│   ├── ai_engine/                     # AI-powered hacking components
│   │   ├── decision_engine/           # Threat decision-making logic
│   │   │   ├── ai_decision.py         # Core AI decision-making
│   │   │   ├── threat_mapper.py       # Maps threats to actions
│   │   │   └── __init__.py            # Submodule initializer
│   │   ├── evasion/                   # Detection avoidance tools
│   │   │   ├── evasion.py             # Evasion strategy implementation
│   │   │   └── __init__.py            # Submodule initializer
│   │   ├── exploitation/              # Automated exploit generation
│   │   │   ├── exploit.py             # Executes exploits
│   │   │   ├── auto_learning.py       # Self-improving exploit logic
│   │   │   └── __init__.py            # Submodule initializer
│   │   ├── models/                    # AI model definitions
│   │   │   ├── base_model.py          # Base class for models
│   │   │   ├── ai_exploit.py          # Exploit-specific AI model
│   │   │   ├── code_analyzer.py       # Vulnerability code analysis
│   │   │   └── __init__.py            # Submodule initializer
│   │   ├── pre_trained_models/        # Pre-trained AI models
│   │   │   ├── codebert_base.pt       # CodeBERT for code analysis
│   │   │   ├── vulnbert_base.pt       # VulnBERT for vuln prediction
│   │   │   └── vulnerability_predictor.pt # General vuln predictor
│   │   ├── reconnaissance/            # Target intel gathering
│   │   │   ├── recon_engine.py        # Core recon logic
│   │   │   └── __init__.py            # Submodule initializer
│   │   ├── red_teaming/               # Adversarial simulations
│   │   │   ├── threat_simulation.py   # Simulates attack scenarios
│   │   │   └── __init__.py            # Submodule initializer
│   │   ├── strategies/                # Advanced AI strategies
│   │   │   ├── hyperdimensional.py    # Hyperdimensional computing
│   │   │   └── neuroplasticity.py     # Adaptive learning logic
│   │   ├── trainers/                  # Model training pipelines
│   │   │   ├── adversarial.py         # Adversarial training
│   │   │   ├── federated.py           # Federated learning
│   │   │   └── __init__.py            # Submodule initializer
│   │   ├── training_pipeline/         # Tool-integrated training
│   │   │   ├── nmap_pipeline.py       # Nmap training integration
│   │   │   ├── sqlmap_pipeline.py     # SQLmap training integration
│   │   │   └── __init__.py            # Submodule initializer
│   │   └── zero_day/                  # Zero-day vuln discovery
│   │       ├── predictor.py           # Predicts zero-days
│   │       ├── zero_day_hunter.py     # Hunts novel threats
│   │       └── __init__.py            # Submodule initializer
│   ├── api/                           # RESTful API services
│   │   ├── server.py                  # Main API server
│   │   ├── auth.py                    # Authentication logic
│   │   ├── routes/                    # API endpoints
│   │   │   ├── bounty.py              # Bug bounty endpoints
│   │   │   ├── exploit.py             # Exploit endpoints
│   │   │   ├── intelligence.py        # Threat intel endpoints
│   │   │   └── scan.py                # Scan endpoints
│   │   ├── middleware/                # API middleware
│   │   │   ├── error_handler.py       # Custom error handling
│   │   │   ├── rate_limiter.py        # Rate limiting
│   │   │   └── input_validation.py    # Input sanitization
│   │   └── monitoring/                # API health tracking
│   │       ├── health.py              # Health check endpoints
│   │       ├── metrics.py             # Performance metrics
│   │       └── __init__.py            # Submodule initializer
│   ├── core/                          # Foundational utilities
│   │   ├── architecture.py            # System architecture defs
│   │   ├── orchestration/             # Workflow coordination
│   │   │   ├── exploit_coordinator.py # Manages exploit flows
│   │   │   ├── scan_coordinator.py    # Manages scan flows
│   │   │   └── __init__.py            # Submodule initializer
│   │   ├── security/                  # Security mechanisms
│   │   │   ├── encryption.py          # Cryptographic functions
│   │   │   ├── authentication.py      # User auth logic
│   │   │   ├── csrf_protection.py     # CSRF defenses
│   │   │   └── tools_manager.py       # Manages tool integration
│   │   └── self_healing/              # Self-repairing systems
│   │       ├── anomaly_detector.py    # Detects anomalies
│   │       ├── auto_recovery.py       # Auto-recovers failures
│   │       └── __init__.py            # Submodule initializer
│   └── experiments/                    # Experimental features
│       └── quantum_test.py            # Quantum computing tests
├── benchmarks/                         # Performance testing
│   ├── penetration.py                 # Pentest benchmarks
│   ├── performance_benchmark.py       # System performance
│   └── scalability.py                 # Scalability tests
├── config/                             # Configuration files
│   ├── app_config.yaml                # App settings
│   ├── logging.yaml                   # Logging config
│   ├── tools_config.json              # Tool configurations
│   └── env/                           # Env-specific configs
│       ├── dev/                       # Development env
│       │   ├── app_config.yaml        # Dev app settings
│       │   └── secrets.env            # Dev secrets
│       └── prod/                      # Production env
│           ├── app_config.yaml        # Prod app settings
│           └── secrets.env            # Prod secrets
├── data/                               # Datasets and resources
│   ├── db/                            # Database files
│   │   ├── database.py                # DB interaction logic
│   │   └── __init__.py                # Submodule initializer
│   ├── exploits/                      # Exploit storage
│   │   └── __init__.py                # Submodule initializer
│   ├── payloads/                      # Payload storage
│   │   └── __init__.py                # Submodule initializer
│   ├── pipeline/                      # Data processing
│   │   ├── data_ingestion.py          # Data intake
│   │   ├── data_processor.py          # Data transformation
│   │   └── data_storage.py            # Data storage
│   └── wordlists/                     # Brute-force wordlists
│       ├── admin-panels.txt           # Admin panel paths
│       ├── big.txt                    # Large wordlist
│       ├── subdomains-top1million-110000.txt # Top subdomains
│       └── __init__.py                # Submodule initializer
├── deployment/                         # Deployment configs
│   ├── docker/                        # Docker setups
│   │   ├── backend/                   # Backend Docker
│   │   │   ├── Dockerfile             # Backend image
│   │   │   └── docker-compose.yml     # Backend composition
│   │   └── frontend/                  # Frontend Docker
│   │       ├── Dockerfile             # Frontend image
│   │       └── docker-compose.yml     # Frontend composition
│   └── kubernetes/                    # Kubernetes configs
│       ├── backend_deployment.yaml    # Backend K8s deployment
│       └── __init__.py                # Submodule initializer
├── docs/                               # Documentation
│   ├── api.md                         # API docs
│   ├── deployment.md                  # Deployment guide
│   ├── Developer_Guides.md            # Dev guide
│   └── README.md                      # Docs overview
├── frontend/                           # User interfaces
│   ├── cli/                           # Command-line tools
│   │   ├── main_cli.py                # Main CLI entry
│   │   └── tool_clis/                 # Tool-specific CLIs
│   │       ├── nmap_cli.py            # Nmap wrapper
│   │       ├── metasploit_cli.py      # Metasploit wrapper
│   │       ├── hashcat_cli.py         # Hashcat wrapper
│   │       └── __init__.py            # Submodule initializer
│   ├── gui/                           # Graphical interface
│   │   ├── dashboard.py               # GUI dashboard
│   │   ├── exploit_view.py            # Exploit visualization
│   │   └── scan_view.py               # Scan visualization
│   └── web_ui/                        # Web interface
│       ├── App.js                     # Main web app
│       ├── index.js                   # Web entry point
│       └── styles/                    # Web styling
│           ├── accessibility.css      # Accessibility styles
│           └── __init__.py            # Submodule initializer
├── .github/                            # GitHub workflows
│   ├── dependabot.yml                 # Dependency updates
│   └── workflows/                     # CI/CD pipelines
│       ├── ci.yml                     # Continuous integration
│       ├── cd.yml                     # Continuous deployment
│       └── security_scan.yml          # Security scans
├── logs/                               # Log storage
│   ├── .gitkeep                       # Placeholder for logs
│   └── README.md                      # Log info
├── plugins/                            # Extensible plugins
│   ├── tools_plugin/                  # Tool plugin example
│   │   ├── plugin.py                  # Plugin logic
│   │   └── __init__.py                # Submodule initializer
│   └── README.md                      # Plugin guide
├── sandbox/                            # Experimental sandbox
│   ├── experimental_feature.py        # Test features
│   └── README.md                      # Sandbox info
├── scripts/                            # Automation scripts
│   ├── setup.sh                       # Env setup
│   ├── deploy.sh                      # Deployment script
│   ├── backup.sh                      # Backup script
│   └── update.sh                      # Update script
├── tests/                              # Test suites
│   ├── ai_engine/                     # AI tests
│   │   ├── test_evasion.py            # Evasion tests
│   │   └── __init__.py                # Submodule initializer
│   ├── api/                           # API tests
│   │   ├── test_routes.py             # Route tests
│   │   └── __init__.py                # Submodule initializer
│   └── README.md                      # Test guide
└── tools/                              # 20+ tool wrappers
    ├── cloud/                         # Cloud tools
    │   ├── aws_warper.py              # AWS integration
    │   └── azure_warper.py            # Azure integration
    ├── crypto_stego/                  # Crypto/stego tools
    │   ├── openssl_warper.py          # OpenSSL wrapper
    │   └── steghide_warper.py         # Steghide wrapper
    ├── exploitation/                  # Exploit tools
    │   ├── metasploit_warper.py       # Metasploit wrapper
    │   ├── cobaltstrike_warper.py     # Cobalt Strike wrapper
    │   └── exploitdb_warper.py        # ExploitDB wrapper
    ├── fuzzing/                       # Fuzzing tools
    │   ├── afl_warper.py              # AFL wrapper
    │   └── boofuzz_warper.py          # Boofuzz wrapper
    ├── gpu/                           # GPU tools
    │   ├── hashcat_warper.py          # Hashcat wrapper
    │   └── __init__.py                # Submodule initializer
    ├── information_gathering/         # Recon tools
    │   ├── nmap_warper.py             # Nmap wrapper
    │   ├── shodan_warper.py           # Shodan wrapper
    │   └── theharvester_warper.py     # TheHarvester wrapper
    ├── passwords/                     # Password tools
    │   ├── hydra_warper.py            # Hydra wrapper
    │   ├── john_warper.py             # John wrapper
    │   └── stegcracker_warper.py      # Stegcracker wrapper
    ├── wireless/                      # Wireless tools
    │   ├── aircrack_warper.py         # Aircrack-ng wrapper
    │   ├── kismet_warper.py           # Kismet wrapper
    │   └── wifite_warper.py           # Wifite wrapper
    └── [16 more categories]           # See full list in project this is huge project
```

---

## 💻 System Requirements

- **OS**: Linux (preferred), macOS, Windows (WSL2 recommended)
- **Python**: 3.9+
- **Node.js**: 16+ (for web UI)
- **Docker**: 20+ (optional)
- **Hardware**: 
  - Minimum: 8GB RAM, 4-core CPU
  - Recommended: 16GB RAM, GPU (for AI training)
- **Tools**: Nmap, Metasploit, Hashcat, etc. (in PATH or installed separately)

---

## 🛠️ Installation

### Quick Start
1. **Clone the Repo**
   ```bash
   git clone https://github.com/BhanuGuragain0/Hacker_AI.git
   cd Hacker_AI
   ```

2. **Set Up Environment**
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate  # Windows: .venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. **Configure Secrets**
   ```bash
   cp config/env/dev/secrets.env .env
   nano .env  # Add API keys, DB creds, etc.
   ```

4. **Launch**
   ```bash
   python launcher.py
   ```

**Trouble?** Check `logs/app.log` or [Troubleshooting](#troubleshooting).

---

## 🎮 Usage

<p align="center">
  <img src="https://via.placeholder.com/600x300.png?text=Hacker_AI+Demo" alt="Hacker_AI Demo" width="600"/>
</p>

### CLI Power
Scan a target:
```bash
python3 frontend/cli/main_cli.py scan --target 192.168.1.1
```
Run Nmap:
```bash
python3 frontend/cli/tool_clis/nmap_cli.py -sV 192.168.1.1
```

### GUI Glory
Launch the dashboard:
```bash
python3 frontend/gui/dashboard.py
```

### Web UI
Serve the web app:
```bash
cd frontend/web_ui
npm install && npm start
```
Visit `http://localhost:3000`.

### API Access
Start the server:
```bash
python3 backend/api/server.py
```
Test it:
```bash
curl http://localhost:8000/api/exploit
```

### Train Models
Fine-tune AI:
```bash
python3 backend/ai_engine/trainers/adversarial.py --model pre_trained_models/codebert_base.pt
```

**More Examples**: [User Guide](./docs/user_guide.md)

---

## ⚙️ Configuration

- **Env Switch**: Set `ENV=dev` or `ENV=prod` in `.env`.
- **Logging**: Tweak `config/logging.yaml`.
- **Models**: Add custom `.pt` files to `backend/ai_engine/pre_trained_models/`.
- **Tools**: Configure paths in `config/tools_config.json`.

---

## 🧪 Testing

Run all tests:
```bash
pytest3 tests/ -v
```
- AI: `pytest tests/ai_engine/`
- API: `pytest tests/api/`
- Benchmarks: `python benchmarks/performance_benchmark.py`

---

## 🌐 Deployment

### Docker
```bash
cd deployment/docker/backend
docker-compose up --build
```

### Kubernetes
```bash
kubectl apply -f deployment/kubernetes/
```

**Details**: [Deployment Guide](./docs/deployment.md)

---

## 🤝 Contributing

1. Fork and branch:
   ```bash
   git checkout -b feat/zero-day-enhance
   ```
2. Code your magic (e.g., improve `zero_day_hunter.py`).
3. PR it!

**Guide**: [Contributing](./docs/Developer_Guides.md#contributing)

---

## 🐞 Troubleshooting

- **Install Fails**: Verify Python version and `pip install -r requirements.txt`.
- **Tool Errors**: Ensure binaries (e.g., `nmap`) are in PATH.
- **API Issues**: Check port 8000 and `.env`.

**Stuck?** Open an [issue](https://github.com/BhanuGuragain0/Hacker_AI/issues).

---

## 🛤️ Roadmap

- [ ] GPU-accelerated training (Q2 2025)
- [ ] Burp Suite and Wireshark wrappers (Q3 2025)
- [ ] Real-time GUI analytics (Q4 2025)
- [ ] AWS/Azure cloud support (2026)

**Ideas?** Share in [Discussions](https://github.com/BhanuGuragain0/Hacker_AI/discussions).

---

## 🌟 Why Hacker_AI?

- **Speed**: AI slashes manual grunt work.
- **Power**: 20+ tools + cutting-edge AI.
- **Future-Proof**: Quantum crypto and self-healing.
- **Open**: Built by a student, for the community.

---

## 📜 License

[MIT License](./LICENSE)—hack away freely!

---

## 📬 Contact

I’m Bhanu Guragain—let’s connect!
- **Email**: [guragainbhanu802@gmail.com](mailto:guragainbhanu802@gmail.com)
- **GitHub**: [Issues](https://github.com/BhanuGuragain0/Hacker_AI/issues)

---

## 🙏 Acknowledgments

- **Coventry University**: For sparking this journey.
- **Open Source**: Nmap, Metasploit, PyTorch, and more.
- **You**: For checking out Hacker_AI!

---

<p align="center">
  <strong>Hacker_AI: Where Student Passion Meets Cybersecurity Innovation.</strong>
</p>
