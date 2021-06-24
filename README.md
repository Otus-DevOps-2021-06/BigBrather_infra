# BigBrather_infra
BigBrather Infra repository

Способ подключения к someinternalhost в одну команду: ssh -J appuser@bastion_ip appuser@privat_someinternalhost_ip
---

HomeWork №5
---
bastion_IP = 178.154.200.77 someinternalhost_IP = 10.128.0.5

HomeWork №6
---
testapp_IP = 130.193.38.108
testapp_port = 9292

HomeWork №7
---
При выполнении домашнего задания с лекции №7, было выполнено:
 1) Основное задание (создание образа с помощью шаблона "Packer"): packer build -var-file=./packer/variables.json ./packer/ubuntu16.json

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
 1) Создана ветка ansible-1;
 2) 
 3) 
 4) 

HomeWork №10
---
При выполнении домашнего задания с лекции №10, было выполнено:
 1) Создана ветка ansible-1;
 2) Установлен Ansible;
 3) Cоздание Inventory файла;
 4) Знакомство с базовыми функциями;
 5) Создание ansible.cfg и конфигурирование;
 6) Написание inventory.yml;
 7) Написание PlayBook сlone.yml (клонирование репозитория);
При выполнении PlayBook с уже склонированным репозиторием, никаких изменений на ВМ не происходит, поэтому значение changed=0. После удаления репозитория и выполнения PlayBook, происходит новое клонирование репозитория, изменения применяются changed=1.
