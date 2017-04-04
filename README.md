# Ansible

### My project to run ansible controller

- Set up infrastructure
    - Ansible controller
        - Install ansible on ubuntu server Virtualbox VM
    - VM Nodes    
        - remote
            - AWS linux
                - instances needs aptitude installed to do updates
        - local
            - linux Virtualbox

- Inventory
    - Specify cmd line
        - `ansible-playbook -i inventory/<hosts-file>  playbooks/<playbook>.yml`
    - Specify from /inventory/ansible.cfg OR /inventory/playbooks/ansible.cfg (latter takes precedence)
        - `[defaults]`
        - `hostfile = /relative/path/to/hosts`
        
- `ansible-playbook  /path/to/playbook.yml`
