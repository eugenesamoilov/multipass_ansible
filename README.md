# multipass ansible



## Getting started
install multipass
install virtualbox
##configure multipass
multipass set local.driver=virtualbox
multipass set local.bridged-network=en1
## create vms
ansible-playbook -i hosts.ini playbook -t create_vm
