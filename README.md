# Vagrantfiles
## bentobox/Ansible/Vagrantfile
  * box = bento/ubuntu-16.04
  * Custom Settings
    * nic2 -> hostonly
    * hostonlyadapter2 -> vboxnet0
    * Memory = 4096 MB

### 1. Synced Folders
  * ~/ansible -> /home/vagrant/ansible
  * ~/python -> /home/vagrant/python

### 2. Ansible
  * latest 'devel' branch

### 3. Extras
  * wajig
  * python colorama
  * python requests  
