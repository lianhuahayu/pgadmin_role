# Deploiement de pgAdmin4 via docker

## Variables par defaut

### Utilisateur par defaut
ansible_user: ubuntu

### pgAdmin4 variable + valeur

pgadmin_container: pgadmin4_container

pgadmin_image: dpage/pgadmin4

pgadmin_port: 80

pgadmin_email: user@domain.com

pgadmin_password: pgadmin_password

pgadmin_data: /backup/pgadmin/data

pgadmin_config: /backup/pgadmin/config

pgadmin_pass: /backup/pgadmin/pass
