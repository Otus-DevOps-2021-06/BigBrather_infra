# BigBrather_infra
Способ подключения к someinternalhost в одну команду: ssh -J appuser@bastion_ip appuser@privat_someinternalhost_ip
---
bastion_IP = 178.154.200.77 someinternalhost_IP = 10.128.0.5
---
testapp_IP = 130.193.38.108
testapp_port = 9292

HomeWork №8
---
При выполнении домашнего задания с лекции №8, было выполнено:
 1) Создана ветка terraform-1;
 2) Установлен Terraform;
 3) Созданы конфигурационные файлы Terraform;
 4) Протестировано создание VM с помощью terraform (образ использовался из сборки предыдущего задания с Packer).