# Set up and secure Pi's
```
ansible-playbook -i inventory/nodes/hosts setup.yaml
```

# Cluster it up
```
ansible-playbook -i inventory/cluster/hosts cluster.yaml
```

# TODO
config that is exported to ~ should have server as IP rather than localhost IP.