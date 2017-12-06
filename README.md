# Install and enable MySQL(Community Edition)


# Pre-requisite 
This ansible playbook requires Ansible 3.0+ and Python 2.7 installed on the host server


# Run

Update the 'hosts; file with 2 hosts(1 master & 1 slave) name, and run the following

ansible-playbook install_ha_mysql.yml --i hosts
