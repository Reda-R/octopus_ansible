# OCTOPUS PROJECT
Welcome to my Octopus project. The purpose of this project is to deploy the application [Popeye project](https://github.com/Reda-R/popeye_docker) onto 5 different machines, without using containers, by using Ansible. (As a bonus, I used vagrant to create severals virtual machines)


### ROLES ASSOCIATED TO THE 5 MACHINES
- **Base**: Role associated to all machines
- **Redis & PostgreSQL**: 2 databases
- **Poll, Worker and Result**: 3 images to run the application


![](/assets/ansible.png "Ansible Logo")
