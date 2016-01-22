# ansible-elasticsearch

go to vagrant directory
> vagrant up

go to ansible directory
> ansible-playbook -i inventory main.yml --private-key="/path/to/your/private/key" -u vagrant
example:- ansible-playbook -i inventory main.yml --private-key="/home/vishwaraj.sodha/.vagrant.d/insecure_private_key" -u vagrant
