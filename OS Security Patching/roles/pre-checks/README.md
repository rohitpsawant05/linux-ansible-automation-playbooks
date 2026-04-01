## Purpose
This role performs **pre-patching validation checks** before security patching begins.
## Tasks Performed
- Gather package facts
- Check current kernel version
- Check system uptime
- Check root filesystem usage
- Display collected system details
## Why This Role Is Important
Pre-check validation helps administrators confirm that the target system is healthy before patching is applied. It also provides a baseline for comparison after the patching process is completed.
## Example Use Cases
- Verify system health before maintenance
- Record kernel version before reboot
- Ensure sufficient disk space exists before patching
