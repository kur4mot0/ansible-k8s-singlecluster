# ansible-k8s-singlecluster
Ansible playbook to implement Single Cluster of Kubernetes.

## First of all
Create at least 2 server, and update the host file with their names.
Update the /etc/hosts

## Second of all
Ensure the connection between of them and your ansible machine.

## Third of all
Ensure the connection using ssh based to those servers.
ssh-copy-id root@<server>

## To run this playbook:
Run this command:
"ansible-playbook -i host kubernetes-full.yaml"
