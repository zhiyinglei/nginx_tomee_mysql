
1. install docker

2. install docker compose

3. cd && mkdir -p .reactor/logs/ && mkdir -p mount_dockers/mysql

4. echo "index in log" > ~/.reactor/logs/index.html

5. git clone https://github.com/zhiyinglei/nginx_tomee_mysql.git

6. cd nginx_tomee_mysql

7. docker-compose up --build

8. visit localhost with your browser

   http://localhost:10080/logs/

   http://localhost:8080/rr/
   
9. mysql shell
   
   mysql -h HOST_IP -P 3306 -ureactor  -pp@ssword
