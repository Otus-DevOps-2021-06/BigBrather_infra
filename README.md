# BigBrather_infra
BigBrather Infra repository

HomeWork №5
---
Способ подключения к someinternalhost в одну команду:
 1) ssh -J appuser@bastion_ip appuser@privat_someinternalhost_ip;
bastion_IP = 178.154.200.77 someinternalhost_IP = 10.128.0.5.

HomeWork №6
---
testapp_IP = 130.193.38.108
testapp_port = 9292

HomeWork №7
---
При выполнении домашнего задания с лекции №7, было выполнено:
 1) Основное задание (создание образа с помощью шаблона "Packer"): **packer build -var-file=./packer/variables.json ./packer/ubuntu16.json**

HomeWork №8
---
При выполнении домашнего задания с лекции №8, было выполнено:
 1) Создана ветка terraform-1;
 2) Установлен Terraform;
 3) Созданы конфигурационные файлы Terraform;
 4) Протестировано создание VM с помощью terraform (образ использовался из сборки предыдущего задания с Packer).

HomeWork №9
---
При выполнении домашнего задания с лекции №9, было выполнено:
 1) Основное задание (разделение на модули, создание stage и prod);
 2) Самостоятельное задание. (Удалить из основной директории: **main.tf**, **outputs.tf**, **terraform.tfvars**, **variables.tf**. Так, как они теперь в stage и prod);
 3) Задание с * (Настройка хранения стейт файла в удаленном **backend.tf**).

HomeWork №10
---
При выполнении домашнего задания с лекции №10, было выполнено:
 1) Создана ветка ansible-1;
 2) Установлен Ansible;
 3) Cоздание Inventory файла;
 4) Знакомство с базовыми функциями;
 5) Создание ansible.cfg и конфигурирование;
 6) Написание **inventory.yml**;
 7) Написание PlayBook **сlone.yml** (клонирование репозитория);
При выполнении PlayBook с уже склонированным репозиторием, никаких изменений на ВМ не происходит, поэтому значение changed=0. После удаления репозитория и выполнения PlayBook, происходит новое клонирование репозитория, изменения применяются changed=1.

HomeWork №11
---
При выполнении домашнего задания с лекции №11, было выполнено:
 1) Создана ветка ansible-2;
 2) Разработы Ansible playbook для instans с application, data base и deploy;
 3) Запуск playbook в нужном порядке производиться командой: **ansible-playbook site.yml**;
 4) Сборки образов Packer были изменены provisioners на Ansible **packer_app.yml** и **packer_db.yml**.

HomeWork №12
---
При выполнении домашнего задания с лекции №11, было выполнено:
 1) Создана ветка ansible-3;
 2) Созданы раздельные роли - app и db;
 3) Описаны окружения prod и stage;
 4) Созданы пользователи, проведена работа с Ansible Vault;
 5) Выполнение playbook в stage окружении: **ansible-playbook playbooks/site.yml**;
 6) Выполнение playbook в prod окружении: **ansible-playbook -i environments/prod/inventory playbooks/site.yml**.
