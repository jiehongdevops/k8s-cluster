# Creating kubernetes cluster
- **Single head node, multiple workers**
- **Practice on Ubuntu 18**
- **Used CNI: Weave**
## vars:
- file: vars/vars
  - servicecidr: cluster cidr, default 10.32.0.0/12
## usage:
- create cluster
```
  ansible-playbook create-cluster.yml
```
- reset cluster
```
  ansible-playbook reset_cluster.yml
```
