# ansible-docker-jenkins
sample of ansible playbook for installation docker, docker-compose and running Jenkins via docker; NGINX & Postgres via docker-compose on localhost for Debian/Ubuntu-based linux systems

usage: ansible-playbook playbook.yml (please set up your host(s) in hosts file)

nginx_postgres.yml suports 2 ways for ansible_service:
- you can modify data in tasks *.yml file
- or use docker-compose.yml and run from a directory where it located
