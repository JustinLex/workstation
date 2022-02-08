# workstation
An ansible playbook containing install scripts for my productivity computer

## How to use

1. Ensure that the community/general collection is installed for Ansible with `ansible-galaxy collection install community.general`
2. Comment/uncomment the scripts you want to use in the "roles" array in char.yml
3. Run `ansible-playbook -K char.yml`, inputting your password for sudo.

## Things that can be installed and configured

### Software
* Enpass
* JetBrains Toolbox
* Kubernetes + Minikube
* Samsung Unified Linux Driver for printers
* Mullvad VPN

### Tweaks (todo)
* Thinkpad battery limits
* Netnod NTP/NTS servers
* Hibernation
* Windows Hello
* Fingerprint
* Biometric/Key-based LUKS unlocking
