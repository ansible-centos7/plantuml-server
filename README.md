This playbook installs docker, docker compose and PlantUML Server on CentOS7.

## Install docker, docker compose and PlantUML Server

Change to root and execute commands below.

```
ansible-galaxy install -r requirements.yml
ansible-playbook -i localhost, -c local install.yml
```


