This automation playbook is designed for installing and configuring Apache Webserver on Linux server. 
To run the playbook please run below command on Master/Control Node (Ansible Master Server).
Make sure the Passwordless SSh has been enabled from Master to target servers before executing any playbook.

# ansible-playbook -i inventory.ini install_apache.yml
