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
<img width="656" height="809" alt="config kibana" src="https://github.com/user-attachments/assets/089c6fc1-b331-43cd-b816-109584755b44" />
.
<img width="656" height="809" alt="config kibana" src="https://github.com/user-attachments/assets/0d5803a7-b3f1-44aa-a9c5-dcc06084e07e" />
.
<img width="1920" height="950" alt="kibana konsole" src="https://github.com/user-attachments/assets/9cd41f72-1fb9-4f7f-87dc-56efaebf95f2" />
.
<img width="1489" height="484" alt="kibana konsole(2)" src="https://github.com/user-attachments/assets/52afa811-e94f-48f9-8467-94280b081e0c" />



# Задание 3. Logstash
Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.



# Задание 4. Filebeat.
Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.

Дополнительные задания (со звёздочкой*)
Эти задания дополнительные, то есть не обязательные к выполнению, и никак не повлияют на получение вами зачёта по этому домашнему заданию. Вы можете их выполнить, если хотите глубже шире разобраться в материале.
