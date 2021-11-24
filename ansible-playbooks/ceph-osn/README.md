# Ceph OSN

### Create Cluster

    ansible-playbook ceph-ansible-playbook.yml -e inventory_dest=/path/to/site/inventory/sdsc-dev/hosts.ini

### Delete Cluster

    ansible-playbook ceph-ansible-playbook.yml -e inventory_dest=/path/to/site/inventory/sdsc-dev/hosts.ini -e state=absent