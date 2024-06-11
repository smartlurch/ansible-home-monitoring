# ansible project to setup netbox and zabbix on my home server

## Getting Started 
1. git pull from github
2. edit inventory file
3. make sure ssh into server works with ssh key
3. run ansible-playbook -i inventory.yml -f main.yml -K
    a. install docker
    b. pull down netbox docker compose
    c. spin up netbox
    d. pull down zabbix docker compose
    e. sping up zabbix
