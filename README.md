# Домашнее задание к занятию "ELK" - `Гусев Алексей`

### Дополнительные материалы, которые могут быть полезны для выполнения задания
1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)
---

### Задание 1. Elasticsearch 

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный. 

*Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name*.

![Название скриншота 1](https://github.com/netolearning777/git_ELK-hw/blob/main/img/VirtualBox_ubuntu-desktop-24_01_09_2026_13_52_50.png)

---
### Задание 2. Kibana

Установите и запустите Kibana.

*Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty*.

![Название скриншота 2](https://github.com/netolearning777/git_ELK-hw/blob/main/img/VirtualBox_ubuntu-desktop-24_01_09_2026_16_03_31.png)

---

### Задание 3. Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.*
![Название скриншота 3](https://github.com/netolearning777/git_ELK-hw/blob/main/img/2026-09-02_13-12-42.png)

---

### Задание 4. Filebeat. 

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.*

![Название скриншота 3](https://github.com/netolearning777/git_ELK-hw/blob/main/img/2026-09-02_14-58-58.png)
