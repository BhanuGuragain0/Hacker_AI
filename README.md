

<p align="center">
  <img src="https://via.placeholder.com/150x150.png?text=Hacker_AI" alt="Hacker_AI Logo" width="150"/>
</p>

<h1 align="center">Hacker_AI</h1>

<p align="center">
  <strong>Unleash the Future of Cybersecurity with AI Precision</strong><br>
  Crafted by <a href="https://github.com/BhanuGuragain0">Bhanu Guragain</a>, a BSc Ethical Hacking & Cybersecurity student at Coventry University.
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

---

## Table of Contents

- [What is Hacker_AI?](#what-is-hacker_ai)
- [Key Features](#key-features)
- [Project Structure](#project-structure)
- [System Requirements](#system-requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Testing](#testing)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [Troubleshooting](#troubleshooting)
- [Roadmap](#roadmap)
- [Why Hacker_AI?](#why-hacker_ai)
- [License](#license)
- [Contact](#contact)
- [Acknowledgments](#acknowledgments)

---

## What is Hacker_AI?

**Hacker_AI** is a cutting-edge, AI-powered cybersecurity toolkit designed to empower ethical hackers, security researchers, and defenders. Created by Bhanu Guragain, a BSc Ethical Hacking & Cybersecurity student at Coventry University, this project blends academic rigor with real-world innovation. It leverages advanced AI models, self-healing systems, and a rich ecosystem of integrated tools to perform tasks like vulnerability assessment, zero-day hunting, and automated exploitation—all with precision and scalability.

Hacker_AI harnesses machine learning to enhance cybersecurity workflows, offering features like predictive zero-day detection, continuous model training, and quantum-ready encryption. Whether you're scanning networks, crafting exploits, or deploying in the cloud, Hacker_AI is your partner in staying ahead of threats.

> **Why Me?** As a Coventry student, I’m driven to fuse theory with practice, building tools that redefine security in an AI-driven world.

---

## ✨ Key Features

| Feature              | Why It Rocks                                                        | Try It Out                                |
|----------------------|--------------------------------------------------------------------|-------------------------------------------|
| **AI-Powered Hacking** | Automate exploits and scans with surgical precision.              | `backend/ai_engine/exploitation/exploit.py` |
| **Zero-Day Hunting**   | Predict and catch novel threats before they strike.              | `backend/ai_engine/zero_day/zero_day_hunter.py` |
| **Continuous Learning**| Evolve your toolkit with self-improving AI models.               | `backend/ai_engine/trainers/`            |
| **Quantum-Ready**      | Future-proof your security with quantum-safe cryptography.       | `backend/core/security/encryption.py`    |
| **Self-Healing**       | Recover from anomalies in real-time with adaptive systems.       | `backend/core/self_healing/`             |
| **Tool Ecosystem**     | Seamlessly integrate classics like Nmap, Metasploit, and more.   | `tools/information_gathering/nmap_warper.py` |
| **Scalable Deployment**| Deploy anywhere—laptop, Docker, or Kubernetes clusters.          | `deployment/docker/`                     |
| **Plugin Power**       | Extend functionality with custom plugins.                       | `plugins/tools_plugin/`                  |
| **Rock-Solid Testing** | Ensure reliability with comprehensive test suites.              | `pytest tests/`                          |

---

## 🚀 Project Structure

Here’s a high-level overview of the Hacker_AI directory structure:

```
Hacker_AI/
├── analytics/                          # Tools for data analysis and visualization
│   ├── dashboard.py                   # Generates interactive analytics dashboards
│   ├── data_pipeline.py               # Manages data ingestion and processing
│   ├── metrics_collector.py           # Collects system performance and security metrics
│   ├── report_generator.py            # Produces detailed analytics reports
│   └── utils.py                       # Helper functions for analytics tasks
├── backend/                            # Core logic, AI engines, and API services
│   ├── ai_engine/                     # AI-powered components for hacking tasks
│   │   ├── decision_engine/           # Decision-making logic for threats
│   │   │   ├── ai_decision.py         # Core AI decision-making script
│   │   │   ├── threat_mapper.py       # Maps detected threats to actions
│   │   │   └── utils.py              # Utility functions for decision engine
│   │   ├── evasion/                   # Detection avoidance techniques
│   │   │   ├── evasion.py             # Implements evasion strategies
│   │   │   └── stealth_mode.py        # Enhances stealth capabilities
│   │   ├── exploitation/              # Automated exploit tools
│   │   │   ├── exploit.py             # Generates and executes exploits
│   │   │   ├── auto_learning.py       # Self-improving exploit algorithms
│   │   │   └── payload_generator.py   # Creates custom exploit payloads
│   │   ├── models/                    # AI model definitions and logic
│   │   │   ├── base_model.py          # Base class for all AI models
│   │   │   ├── ai_exploit.py          # Exploit-specific AI model
│   │   │   └── code_analyzer.py       # Analyzes code for vulnerabilities
│   │   ├── pre_trained_models/        # Pre-trained AI model files
│   │   │   ├── codebert_base.pt       # Pre-trained CodeBERT model
│   │   │   ├── vulnerability_predictor.pt # Predicts code vulnerabilities
│   │   │   └── threat_classifier.pt   # Classifies potential threats
│   │   ├── reconnaissance/            # Reconnaissance tools and engines
│   │   │   ├── recon_engine.py        # Core reconnaissance logic
│   │   │   └── network_scanner.py     # Scans networks for targets
│   │   ├── trainers/                  # Training modules for AI models
│   │   │   ├── adversarial.py         # Adversarial training techniques
│   │   │   ├── federated.py           # Federated learning implementations
│   │   │   └── trainer_utils.py       # Helper functions for training
│   │   └── zero_day/                  # Zero-day vulnerability discovery
│   │       ├── predictor.py           # Predicts potential zero-day vulnerabilities
│   │       ├── zero_day_hunter.py     # Hunts for novel threats
│   │       └── signature_generator.py # Generates signatures for zero-days
│   ├── api/                           # RESTful API for external interaction
│   │   ├── server.py                  # Main API server implementation
│   │   ├── auth.py                    # Authentication and authorization logic
│   │   ├── routes/                    # API endpoint definitions
│   │   │   ├── exploit.py             # Endpoints for exploit operations
│   │   │   ├── intelligence.py        # Threat intelligence endpoints
│   │   │   └── recon.py               # Reconnaissance endpoints
│   │   └── middleware/                # API middleware for security and performance
│   │       ├── error_handler.py       # Custom error handling
│   │       ├── rate_limiter.py        # Limits API request rates
│   │       └── logger.py              # Logs API activity
│   └── core/                          # Foundational utilities and security
│       ├── architecture.py            # Defines system architecture
│       ├── orchestration/             # Coordinates multiple AI engines
│       │   ├── exploit_coordinator.py # Manages exploit workflows
│       │   ├── scan_coordinator.py    # Coordinates scanning operations
│       │   └── task_scheduler.py      # Schedules automated tasks
│       ├── security/                  # Security-related mechanisms
│       │   ├── encryption.py          # Cryptographic functions
│       │   ├── authentication.py      # User authentication logic
│       │   └── firewall.py            # Internal firewall rules
│       └── self_healing/              # Self-repairing systems
│           ├── anomaly_detector.py    # Detects anomalies in system behavior
│           ├── auto_recovery.py       # Automates recovery from failures
│           └── health_monitor.py      # Monitors system health
├── config/                             # Configuration files for the project
│   ├── app_config.yaml                # General application settings
│   ├── logging.yaml                   # Logging configuration
│   ├── secrets.yaml                   # Sensitive configuration data
│   └── env/                           # Environment-specific configurations
│       ├── dev/                       # Development environment
│       │   ├── secrets.env            # Sensitive variables for dev
│       │   └── db_config.yaml         # Database settings for dev
│       └── prod/                      # Production environment
│           ├── secrets.env            # Sensitive variables for prod
│           └── db_config.yaml         # Database settings for prod
├── data/                               # Datasets and resources
│   ├── db/                            # Database-related files
│   │   ├── database.py                # Database interaction logic
│   │   └── schema.sql                 # Database schema definition
│   ├── exploits/                      # Exploit-related data
│   │   ├── exploit_db.csv             # Database of known exploits
│   │   └── custom_exploits.json       # Custom exploit definitions
│   ├── payloads/                      # Attack payloads
│   │   ├── shellcode.bin              # Precompiled shellcode
│   │   └── custom_payload.py          # Script to generate payloads
│   └── wordlists/                     # Wordlists for brute-forcing
│       ├── dirs_big.enc               # Encrypted directory wordlist
│       ├── subdomains.enc             # Encrypted subdomain wordlist
│       └── passwords.enc              # Encrypted password wordlist
├── deployment/                         # Deployment configurations
│   ├── docker/                        # Docker configurations
│   │   ├── backend/                   # Backend Docker setup
│   │   │   ├── Dockerfile             # Backend Docker image
│   │   │   └── docker-compose.yml     # Backend service composition
│   │   └── frontend/                  # Frontend Docker setup
│   │       ├── Dockerfile             # Frontend Docker image
│   │       └── docker-compose.yml     # Frontend service composition
│   └── kubernetes/                    # Kubernetes deployment files
│       ├── backend_deployment.yaml    # Backend K8s deployment
│       ├── frontend_deployment.yaml   # Frontend K8s deployment
│       └── service.yaml               # K8s service definitions
├── docs/                               # Project documentation
│   ├── api.md                         # API usage and endpoints
│   ├── deployment.md                  # Deployment instructions
│   ├── Developer_Guides.md            # Developer and contribution guide
│   └── README.md                      # Project overview and setup
├── frontend/                           # User interface components
│   ├── cli/                           # Command-line interfaces
│   │   ├── main_cli.py                # Main CLI entry point
│   │   └── tool_clis/                 # Tool-specific CLIs
│   │       ├── nmap_cli.py            # Nmap CLI wrapper
│   │       ├── metasploit_cli.py      # Metasploit CLI wrapper
│   │       └── recon_cli.py           # Reconnaissance CLI
│   ├── gui/                           # Graphical user interface
│   │   ├── dashboard.py               # GUI dashboard for analytics
│   │   ├── exploit_view.py            # Visualizes exploit operations
│   │   └── settings.py                # GUI configuration settings
│   └── web_ui/                        # Web-based interface
│       ├── App.js                     # Main web app script
│       ├── index.js                   # Web app entry point
│       └── styles.css                 # Web UI styling
├── logs/                               # Log files
│   ├── app.log                        # General application logs
│   ├── error.log                      # Error-specific logs
│   └── access.log                     # API access logs
├── plugins/                            # Extensible plugin system
│   ├── tools_plugin/                  # Example plugin for tools
│   │   ├── plugin.py                  # Plugin implementation
│   │   └── config.yaml                # Plugin configuration
│   └── custom_plugin/                 # Placeholder for custom plugins
│       └── README.md                  # Instructions for plugin creation
├── scripts/                            # Automation and utility scripts
│   ├── setup.sh                       # Sets up the environment
│   ├── deploy.sh                      # Deploys the project
│   ├── test_runner.sh                 # Runs all tests
│   └── backup.py                      # Backs up critical data
├── tests/                              # Test suites for validation
│   ├── ai_engine/                     # AI component tests
│   │   ├── test_evasion.py            # Tests evasion logic
│   │   ├── test_exploitation.py       # Tests exploitation logic
│   │   └── test_recon.py              # Tests reconnaissance logic
│   ├── api/                           # API tests
│   │   ├── test_routes.py             # Tests API endpoints
│   │   └── test_auth.py               # Tests authentication
│   └── core/                          # Core utility tests
│       └── test_security.py           # Tests security features
└── tools/                              # Wrappers for external tools
    ├── information_gathering/         # Reconnaissance tools
    │   ├── nmap_warper.py             # Nmap integration
    │   └── whois_lookup.py            # Whois lookup integration
    ├── exploitation/                  # Exploitation tools
    │   ├── metasploit_warper.py       # Metasploit wrapper
    │   └── sqlmap_warper.py           # SQLmap wrapper
    └── wireless/                      # Wireless attack tools
        ├── aircrack_warper.py         # Aircrack-ng wrapper
        └── wifite_warper.py           # Wifite wrapper
```

**Want More?** Check the [Full Structure](./docs/project_structure.md).

---

## 💻 System Requirements

- **OS**: Linux, macOS, or Windows (WSL recommended for Windows)
- **Python**: 3.9+
- **Node.js**: 16+ (for web UI)
- **Docker**: 20+ (optional, for containerized deployment)
- **Hardware**: 8GB RAM, 4-core CPU (16GB RAM and GPU recommended for AI training)
- **Tools**: Nmap, Metasploit, and other wrapped tools (installed separately or via system PATH)

---

## 🛠️ Installation

### Prerequisites
- Install Python: `sudo apt install python3.9` (Linux) or download from [python.org](https://www.python.org)
- Install Git: `sudo apt install git`
- Install Docker (optional): `sudo apt install docker.io`
- Install Node.js (for web UI): `sudo apt install nodejs npm`
- Ensure `pip`: `python -m ensurepip`

### Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/BhanuGuragain0/Hacker_AI.git
   cd Hacker_AI
   ```

2. **Set Up Python Environment**
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. **Configure Environment**
   ```bash
   cp config/env/dev/secrets.env .env
   ```
   Edit `.env` with your keys (e.g., `API_KEY=your_secret_key`).

4. **Launch the Toolkit**
   ```bash
   python3 launcher.py
   ```
   Logs are in `logs/app.log` if issues arise.

---

## 🎮 Usage

<p align="center">
  <img src="https://github.com/BhanuGuragain0/Hacker_AI/raw/main/assets/demo.gif" alt="Hacker_AI Demo" width="600"/>
</p>

### Command Line Interface (CLI)
Run scans or exploits via the main CLI:
```bash
python frontend/cli/main_cli.py scan --target 192.168.1.1
```
Or use tool-specific CLIs:
```bash
python frontend/cli/tool_clis/nmap_cli.py scan --target 192.168.1.1
```

### Graphical User Interface (GUI)
Launch the dashboard:
```bash
python frontend/gui/dashboard.py
```

### Web UI
Build and serve the web interface:
```bash
cd frontend/web_ui
npm install
npm run build
npm start
```
Access at `http://localhost:3000` (default port).

### API
Start the API server:
```bash
python backend/api/server.py
```
- Health check: `curl http://localhost:8000/health`
- Exploit data: `curl http://localhost:8000/api/exploit`

### Docker
Run the backend in a container:
```bash
cd deployment/docker/backend
docker-compose up --build
```

**Details**: See [User Guide](./docs/user_guide.md).

---

## ⚙️ Configuration

- **Environment**: Switch between `dev` and `prod` by setting `ENV=dev` or `ENV=prod` and using the respective `secrets.env`.
- **Logging**: Customize via `config/logging.yaml`.
- **AI Models**: Pre-trained models are in `backend/ai_engine/pre_trained_models/`. Add custom models or download additional ones as needed.
- **Database**: Uses SQLite by default (`data/db/database.py`). Configure via `.env` if switching to PostgreSQL or others.

---

## 🧪 Testing

Run the full test suite:
```bash
pytest tests/ -v
```
- AI tests: `pytest tests/ai_engine/`
- API tests: `pytest tests/api/`
- Benchmarks: `python benchmarks/penetration.py`

**More**: [Testing Guide](./docs/Developer_Guides.md#testing).

---

## 🌐 Deployment

- **Docker**: Use `deployment/docker/` for backend and frontend containers.
  ```bash
  cd deployment/docker/backend
  docker-compose up --build
  ```
- **Kubernetes**: Deploy scalably with `deployment/kubernetes/backend_deployment.yaml`.
  ```bash
  kubectl apply -f deployment/kubernetes/
  ```

**Guide**: [Deployment Doc](./docs/deployment.md).

---

## 🤝 Contributing

Join the mission:
1. Fork and branch:
   ```bash
   git checkout -b feat/your-feature
   ```
2. Hack away:
   - AI: `backend/ai_engine/`
   - Tools: `tools/`
   - Plugins: `plugins/`
3. Submit a PR.

**Guidelines**: [Contribution Guide](./docs/Developer_Guides.md#contributing).

---

## 🐞 Troubleshooting

- **Installation Fails**: Ensure Python 3.9+ and dependencies are installed. Check `requirements.txt`.
- **CLI Errors**: Verify tool binaries (e.g., Nmap) are in your PATH.
- **API Down**: Confirm port 8000 is free and `.env` is set.
- Logs: Check `logs/app.log`.

**More Help**: File an [issue](https://github.com/BhanuGuragain0/Hacker_AI/issues).

---

## 🛤️ Roadmap

- GPU-accelerated training
- More tool wrappers (Burp Suite, Wireshark)
- Enhanced GUI with real-time analytics
- Cloud-native integrations (AWS, Azure)

---

## 🌟 Why Hacker_AI?

- **Fast**: AI-driven automation cuts time.
- **Flexible**: Plugins and wrappers adapt to your needs.
- **Secure**: Quantum-ready encryption and self-healing.
- **Community**: A student-led project open to collaboration.

---

## 📜 License

Licensed under the [MIT License](./LICENSE)—free to use and innovate.

---

## 📬 Contact

I’m Bhanu Guragain, a Coventry University student pushing the boundaries of cybersecurity.
- **Email**: [guragainbhanu802@gmail.com](mailto:guragainbhanu802@gmail.com)
- **Issues**: [GitHub Issues](https://github.com/BhanuGuragain0/Hacker_AI/issues)

---

## 🙏 Acknowledgments

- Coventry University for inspiring this journey.
- Open-source tools like Nmap, Metasploit, and PyTorch.
- Contributors—your support fuels Hacker_AI!

---

<p align="center">
  <em>Hacker_AI: A Student’s Vision Meets the Edge of Security.</em>
</p>
