# rpi-beep-boot
Ansible script to make bootable SDCard for RPI4 with Ubuntu image

## Requirements:
- [ansible](https://www.ansible.com/)
- Any linux distro

## Usage:
**⚠️!!Warning!!⚠️ This will wipe all your data so ensure that the device is safe to be wiped out.**
```sh
ansible-playbook playbook.yml -K 
```
Update `vars.yml` to change/update devices
