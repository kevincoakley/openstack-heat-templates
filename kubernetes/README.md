# Kubernetes

### Create cluster-1

    openstack stack create -t k8s.yaml --parameter key_name=<key_name> cluster-1

### Added a 4th node to cluster-1

    openstack stack update -t k8s.yaml --parameter key_name=<key_name> --parameter num_nodes=4 cluster-1
