# Домашнее задание к занятию «ELK» Погребенко Александр

# Задание 1. Elasticsearch
Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.

Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.
<img width="845" height="651" alt="elc" src="https://github.com/user-attachments/assets/5d56f1ca-f503-4d91-b830-5349e9a3f92f" />
.

<img width="690" height="257" alt="elc status" src="https://github.com/user-attachments/assets/57a0d6ac-b3c9-44bc-bef6-3d218b2d0093" />
.

<img width="836" height="309" alt="cluster name" src="https://github.com/user-attachments/assets/92b9d0ae-2ba2-439e-af0d-a3f9465aab9c" />
.

<img width="681" height="300" alt="curl elc" src="https://github.com/user-attachments/assets/d0a80dd9-a457-455f-8b34-0e667c13eaf6" />

.


# Задание 2. Kibana
Установите и запустите Kibana.

Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.
.
<img width="872" height="232" alt="kibana" src="https://github.com/user-attachments/assets/1aa24706-8912-4d00-899d-3ff81463446e" />
.
<img width="656" height="809" alt="config kibana" src="https://github.com/user-attachments/assets/089c6fc1-b331-43cd-b816-109584755b44" />
.
<img width="819" height="492" alt="kibana status" src="https://github.com/user-attachments/assets/530dd765-a0d4-41ba-95d5-3555f7454441" />

.
<img width="1918" height="952" alt="kibana konsole" src="https://github.com/user-attachments/assets/57275278-a36f-45a4-a119-2f3ef491c96a" />

.
<img width="1920" height="951" alt="kibana konsole(2)" src="https://github.com/user-attachments/assets/474576d9-e7bf-4bac-a157-3d994053f4b0" />





# Задание 3. Logstash
Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

<img width="733" height="110" alt="logstash" src="https://github.com/user-attachments/assets/d267cc7d-eebb-4e15-99c3-b7f3e29a7b8e" />
.
<img width="955" height="345" alt="logstash status" src="https://github.com/user-attachments/assets/65ab160a-e45b-426c-af05-d9e41b4a8a97" />

.
<img width="1920" height="951" alt="logstash-nginx" src="https://github.com/user-attachments/assets/e56b492b-b93c-48c2-9fec-2d37f6bba237" />
.
<img width="1919" height="953" alt="logstash-nginx(2)" src="https://github.com/user-attachments/assets/f36571cf-1774-44a9-bf30-c6ac2302d609" />
.
<img width="1918" height="692" alt="logstash-nginx(3)" src="https://github.com/user-attachments/assets/7f3e0fb1-7a80-4b60-98cc-1b084ef0d534" />


# Задание 4. Filebeat.
Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.

<img width="749" height="170" alt="Filebeat" src="https://github.com/user-attachments/assets/e2291806-5f0b-4c50-a685-284bb52c4510" />
.
<img width="1918" height="951" alt="nginx-Filebeat" src="https://github.com/user-attachments/assets/efb1f24b-a554-4e5e-b70e-f6a147179364" />
.
<img width="1918" height="595" alt="nginx-Filebeat (2)" src="https://github.com/user-attachments/assets/8cc74349-25b9-4dd9-9375-3e71c35a6f3a" />
.
<img width="1919" height="948" alt="nginx-Filebeat (3)" src="https://github.com/user-attachments/assets/c78c8f5d-fe35-4036-91cc-90835a7db7a7" />


