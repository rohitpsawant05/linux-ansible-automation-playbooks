## Purpose
This role performs **security patching for RHEL-based systems** in a structured and controlled manner.
## Tasks Performed
- Perform sanity reboot before patching
- Apply security patches
- Check whether reboot is required
- Reboot server after patching if necessary
- Display patching results
## Why This Role Is Important
RHEL systems often require controlled patching workflows to ensure system stability and compliance. Separating this logic into its own role improves maintainability and allows OS-specific patching behavior.
## Supported Systems
- Red Hat Enterprise Linux
- CentOS
- Rocky Linux
- AlmaLinux
