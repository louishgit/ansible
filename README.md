# Ansible

### My project to run ansible controller

- aws - instance needs aptitude installed to do updates

- inventory
    - specify cmd line
        - ansible-playbook -i inventory/<hosts-file>  playbooks/<playbook>.yml
    - specify from /inventory/ansible.cfg OR /inventory/playbooks/ansible.cfg (latter takes precedence)
        - [defaults]
        - hostfile = /relative/path/to/hosts
        
- ansible-playbook  /path/to/playbook.yml
