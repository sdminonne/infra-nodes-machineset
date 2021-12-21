# infra-nodes-machineset

Goal of this repository is to prototype observability pods spreading across openshift infra nodes.


### Granting access to cluster
Through kubeconfig file (for the moment)

### Creating the infra sets
```shell
KUBECONFIG=<kubeconfig file path>  ansible-playbook playbooks/provision-infra-machinesets.yaml
```
Tested only on AWS.


### References
https://docs.openshift.com/container-platform/4.9/machine_management/creating-infrastructure-machinesets.html
