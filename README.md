# Prometheus

This repository contains Shell scripts and configurations for setting up and managing Prometheus, an open-source systems monitoring and alerting toolkit.

## Features

- Automated setup of Prometheus server
- Configuration management for Prometheus alerts and rules
- Utility scripts for monitoring and maintaining system health
- Customizable scripts for your environment

## Requirements

- **Shell**: Ensure a compatible shell environment (e.g., Bash or Zsh)
- **Dependencies**: Any required tools or packages (e.g., `curl`, `wget`, `systemd`)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/kejhy93/prometheus.git
   cd prometheus
   ```

2. Make scripts executable:
  ```bash
  chmod +x *.sh
  ```
Run the setup script (if available):
```bash
./setup.sh
```
Usage

Start Prometheus:
```bash
./start-prometheus.sh
```
Stop Prometheus:
```bash
./stop-prometheus.sh
```
Check Status:
```bash
./status.sh
```
File Structure

    setup.sh: Script for initial setup of Prometheus
    start-prometheus.sh: Script to start Prometheus server
    stop-prometheus.sh: Script to stop Prometheus server
    rules/: Directory for storing custom alerting rules
    configs/: Directory for Prometheus configuration files

Contributing

Contributions are welcome! Please open an issue or submit a pull request if you'd like to improve the scripts or add new features.
License

This project is licensed under the MIT License.
Acknowledgments

    Prometheus - The monitoring and alerting toolkit
    Open-source community for contributing to the ecosystem
