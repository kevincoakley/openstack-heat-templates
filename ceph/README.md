# Ceph

### Create cluster-1

    openstack stack create -t ceph.yaml --parameter key_name=<key_name> cluster-1

### Create cluster with different management network

    openstack stack create -t ceph.yaml --parameter key_name=<key_name> ceph --parameter management_net=kcoakley_2_network cluster-1

### Create cluster with 5 osd servers

    openstack stack create -t ceph.yaml --parameter key_name=<key_name> --parameter num_osds=5 ceph
 
### Show the output from the stack

    openstack stack output show ceph --all

### Delete the stack

    openstack stack delete ceph -y
