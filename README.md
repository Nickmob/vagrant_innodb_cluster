# vagrant_innodb_cluster
Запуск трёх нод для Oracle InnoDB Cluster

Ansible ставит mysql-server и mysql-shell.

```
vagrant up

cd provision

ansible-playbook playbooks/environment.yml

vagrant ssh mysql1

vagrant ssh mysql2

vagrant ssh mysql3

```