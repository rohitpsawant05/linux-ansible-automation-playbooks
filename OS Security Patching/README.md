# Ansible Role-Based OS Security Patching
This project demonstrates a **role-based Ansible automation workflow** for performing **OS security patching** on Linux servers in a structured and reusable manner.
## Project Objective
The goal of this automation is to perform OS patching in a controlled sequence:
1. **Pre-check**
2. **Security patching**
3. **Sanity reboot**
4. **Post-check validation**
The patching logic is separated based on operating system type:
- **RHEL-based servers**
- **Ubuntu-based servers**
This makes the automation easier to maintain, extend, and troubleshoot.
---
## Project Structure
```text
os-patching-role-based/
├── inventory
│   └── hosts.ini
├── patching.yml
└── roles
   ├── pre-check
   ├── patch-rhel
   ├── patch-ubuntu
   └── post-check

How to Run
# ansible-playbook -i inventory/hosts.ini patching.yml
