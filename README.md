# Description
This is ansible-playbook which deploy wordpress(based on apache2, php 7.4) + mysql db in Docker containers on clear Ubuntu server(without docker).
Also this playbook deploy haproxy and certbot on your host machine to set up SSL.

## Requirements
You should have ansible on your host machine, with ssh-key of necessary host.
There are necessary to change all.pem to your own certificate for your domain.


## Deploy
```
apt install ansible
cd /etc/ansible/
mkdir playbooks && cd playbooks
git clone https://github.com/setlmans/wordpress_docker.git
ansible-playbook deploy-wp.yml
```
## Postconditions
Necessary to set up SSL connection on Apache2 inside the docker-container.
