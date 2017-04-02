# ansible

My project to run ansible controller

aws - instance needs aptitude installed to do updates
  tasks:
    - name: install apt requirements
      become: yes
      become_method: sudo
      apt: 
          pkg=aptitude