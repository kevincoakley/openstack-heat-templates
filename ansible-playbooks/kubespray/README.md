# Kubespray

### Create Cluster

    ansible-playbook kubespray-playbook.yml -e inventory_dest=/path/to/inventory.ini

### Delete Cluster

    ansible-playbook kubespray-playbook.yml -e inventory_dest=/path/to/inventory.ini -e state=absent