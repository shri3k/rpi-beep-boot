# rpi-beep-boot
Ansible script to make bootable SDCard for RPI4 with [Ubuntu ARM](https://ubuntu.com/download/raspberry-pi) image

## Requirements:
- [ansible](https://www.ansible.com/)
- Any linux distro

## Usage:
**⚠️!!Warning!!⚠️ This will wipe all your data so ensure that the device is safe to be wiped out.**
Before running the script, update `vars.yml` to change/update devices that needs to be bootable.

```sh
ansible-playbook playbook.yml -K 
```

