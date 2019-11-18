# 部署ubuntu_django_cinema docker镜像
已安装好docker环境
```shell
docker load --input ubuntu_django_cinema
docker run -p 8080:8000 -it ubuntu:django bin/bash
cd /root/Cinema
python manage.py runserver 0.0.0.0:8000
```
