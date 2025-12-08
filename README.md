# trollface-ansible

## description

homelab cloning vms on host vmware workstation via master-vm using ansible

### requirements
```bash
apt install ansible
apt install python3-pip
pip3 install pyvmomi
ansible-galaxy collection install community.vmware
```
### tested on
- host: Windows 10.0.19045
- vm: Ubuntu 24.04.3 LTS
- hypervisor: VMware 17.6.4 - 24832109
