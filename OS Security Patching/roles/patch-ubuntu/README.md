## Purpose
This role performs **patching operations for Ubuntu-based systems** using Ansible.
## Tasks Performed
- Perform sanity reboot before patching
- Update apt package cache
- Apply available package upgrades
- Check if reboot is required
- Reboot system if necessary
- Display patching results
## Why This Role Is Important
Ubuntu systems use a different package management and reboot-check mechanism compared to RHEL systems. Keeping this logic separate improves readability and simplifies troubleshooting.
## Supported Systems
- Ubuntu
- Debian-based distributions
