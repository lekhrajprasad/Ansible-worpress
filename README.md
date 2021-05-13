# Ansible-worpress

- provide your pem key
- change the ipaddress in myhosts and vars/myvars.yml, One ip represnt MariaDB server and other for applicationServer
- ansible-playbook main.yml -v
- to encript values of vars/myvars.yml with password, run below command
- ansible-vault encript var/myvars.yml
- to decript
- ansible-vault decrypt var/myvars.yml
- provide passwd which was used for encryption
