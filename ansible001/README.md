# Cofiguración de Ansible

## Primer paso, instalación del servidor web mendiante ansible.
```
ansible-playbook -i ../hosts webserver.yml
```
## Segundo paso, instalación del servidor de bases de datos mendiante ansible.
```
ansible-playbook -i ../hosts mysqlserver.yml
```

