Домашняя работа по Ansible. Работа с roles
1. Установка role `ansible-galaxy install -r requirements.yml -p ./roles/`
2. Установка collection `ansible-galaxy collection install -r requirements.yml`
2. Заменить hosts файле `inventory/prod.yml`
3. Выполнение playbook `ansible-playbook -i inventory/prod.yml site.yml`

См: [playbook](https://github.com/FunUndead/ansible-homework-04)