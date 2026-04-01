## Purpose
This role performs **post-patching validation checks** after the patching workflow is completed.
## Tasks Performed
- Check kernel version after patching
- Check uptime after reboot
- Check disk usage
- Verify host reachability using ping
- Display final system state
## Why This Role Is Important
Post-check validation ensures that the server has come back online successfully and remains healthy after patching and reboot operations.
## Example Use Cases
- Validate successful reboot
- Confirm system accessibility
- Compare kernel version before and after patching
