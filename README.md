# Ansible Scripts


## Scripts

* 3dprinter-update.yaml -- update the 3D printers

## Run the script

### 3dprinter-update.yaml

* ansible-playbook -T 30 -b --ask-become-pass -i servers.ini 3dprinter-update.yaml
