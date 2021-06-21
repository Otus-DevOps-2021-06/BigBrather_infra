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

HomeWork №7
---
При выполнении домашнего задания с лекции №8, было выполнено:
 1) Создана ветка terraform-1;
 2) Установлен Terraform;
 3) Созданы конфигурационные файлы Terraform;
 4) Протестировано создание VM с помощью terraform (образ использовался из сборки предыдущего задания с Packer).
