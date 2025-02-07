# Домашнее задание к занятию «ELK»

# Задание 1. Elasticsearch
- Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.
- Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.

# Решение
  - ![image](https://github.com/user-attachments/assets/3d7d4d23-e11c-4f4e-9f3c-60cd9373a11c)
 
# Задание 2. Kibana
- Установите и запустите Kibana.
- Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.

# Решение
-  ![image](https://github.com/user-attachments/assets/686d4e2c-60e5-42fc-ac86-7f7865a93c6f)

# Задание 3. Logstash
- Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.
- Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

# Решение
- ![image](https://github.com/user-attachments/assets/5ef8b213-c201-4099-9986-278a771d3002)
- ![image](https://github.com/user-attachments/assets/404331cf-5b85-4dc0-8466-178ced250572)

# Задание 4. Filebeat.
- Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.
- Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.  

# Решение
- ![image](https://github.com/user-attachments/assets/f0ad941c-ecdb-47ab-badf-480f22fca07c)
- ![image](https://github.com/user-attachments/assets/56edd652-6afe-4b65-828e-32f64c128fb1)

