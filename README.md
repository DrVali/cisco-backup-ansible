backup cisco Switches with Ansible.

This repository contains an Ansible playbook and an inventory file to backup the configuration on cisco switches. The playbook is designed to be flexible and scalable, allowing you to backup from a large number of switches.

for run and get backup use this command in terminal ===============> ansible-playbook -i cisco_sw_hosts.yml cisco_sw_backup.yml 



you can decrypt vault.yml with this command:  ansible-vault decrypt vault.yml       <<<<<<<<<<<<< for security
                                                            encrypt               
