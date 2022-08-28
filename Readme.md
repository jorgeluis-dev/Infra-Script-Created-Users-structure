# Project Structure created for Linux Server Studies

## Directories

/public /adm /ven /sec

## Groups

GRP_ADM GRP_VEN GRP_SEC

## List of users[
    carlos
    maria
    joao
    debora
    sebastiana
    roberto
    josefina
    amanda
    rogerio
]

## Project rules and steps

-Delete previously created directories, files, groups and users;

-All provisioning must be done in a Bash Script file;

-The owner of all directories created will be the root user;

-All users will have full permissions within the public directory;

-Users of each group will have full permission within their respective directory;

-Users will not be able to have read, write and execute permissions in directories of departments that they do not belong to;

-Upload created script file to your GitHub account.
========================================================
Commands used in the Linux terminal

1.PATH
mkdir /publico
mkdir /adm
mkdir /ven
mkdir /sec

2.GROUPS
groupadd GRP_ADM
groupadd GRP_VEN
groupadd GRP_SEC

3.Users
useradd carlos -c "Usuário convidado" -s /bin/bash -m -p $(openssl passwd -crypt Senha123)
useradd maria -c "Usuário convidado" -s /bin/bash -m -p $(openssl passwd -crypt Senha123)
useradd joao -c "Usuário convidado" -s /bin/bash -m -p $(openssl passwd -crypt Senha123)
useradd debora -c "Usuário convidado" -s /bin/bash -m -p $(openssl passwd -crypt Senha123)
useradd sebastiana -c "Usuário convidado" -s /bin/bash -m -p $(openssl passwd -crypt Senha123)
useradd roberto -c "Usuário convidado" -s /bin/bash -m -p $(openssl passwd -crypt Senha123)
useradd josefina -c "Usuário convidado" -s /bin/bash -m -p $(openssl passwd -crypt Senha123)
useradd amanda -c "Usuário convidado" -s /bin/bash -m -p $(openssl passwd -crypt Senha123)
useradd rogerio -c "Usuário convidado" -s /bin/bash -m -p $(openssl passwd -crypt Senha123)






