# ansible
Ansible playbook examples

Lauch docker container :

```bash
docker run -t -d -p 443:443 -p 8080:8080 -e SERVER_NAME=localhost --privileged  --name=tower ybalt/ansible-tower  
```