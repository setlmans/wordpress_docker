# Description
This is ansible-playbook which deploy wordpress(based on apache2, php 7.4) + mysql db in Docker containers.
Also this playbook deploy haproxy and certbot on your host machine to set up SSL.

# Requirements
There are necessary to change all.pem to your own certificate for your domain.
You should have ansible on your host machine

# Install





# postconditions
Necessary to set up SSL connection on Apache2 inside the docker-container.
