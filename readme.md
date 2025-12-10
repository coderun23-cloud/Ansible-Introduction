# Network Automation with Ansible

## 📋 Project Overview
Automate Access point using Ansible by changing hostname.

## 🚀 Quick Start
```bash
# Clone the repository
git clone https://github.com/yourname/ansible-network-automation.git
cd ansible-network-automation

# Install dependencies
pip install -r requirements.txt
ansible-galaxy install -r requirements.yml

# Run a playbook
ansible-playbook -i inventory/development.ini playbooks/network/backup_configs.yml
