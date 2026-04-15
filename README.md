# Network Automation using Ansible + GitHub Actions

## Features
- VLAN automation
- Config backup
- CI/CD integration
- Secure credentials using GitHub Secrets

## Usage

1. Add devices in inventory/hosts.yml
2. Add GitHub secrets:
   - ANSIBLE_USER
   - ANSIBLE_PASS
3. Push code to GitHub

## Run locally

ansible-playbook playbooks/vlan.yml