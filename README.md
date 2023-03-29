# multipass ansible


## Getting started
install multipass
install virtualbox
## Configure multipass
multipass set local.driver=virtualbox
multipass set local.bridged-network=en1
## Create vms
ansible-playbook -i hosts.ini playbook -t create_vm
