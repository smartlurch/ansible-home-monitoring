# TODO list for Project

## Netbox
1. find all env files that need changing
2. find all secret vars that need to be changed
3. use ansible + ansible vault to set secrets and create/change env files for netbox
4. recreate containers and test
5. setup and save user/pass for home netbox in bitwarden

## Zabbix
1. find secrets/env files that need to be changed
2. use ansible vault to set secrets
3. recreate and test
4. setup and save home zabbix user/pass in bitwarden

## proxy
1. decide ssl proxy to use caddy vs treafik vs nginx proxy manager
2. implement and config proxy for self signes certs
3. lookinto getting domain
4. reconfig proxy to use dns challenge and lets encrypt for legit ssl certs for my domain

## further testing
1. creste playbook to test reading from netbox and creating device in zabbix
2. reseaech and implement netbox as ansible inventoryt
3. fully build out netbox for home

