### 基础操作
sudo docker build -t svc-api:test .

sudo docker exec -it svc-api  /bin/bash

sudo docker images

sudo docker rmi -f a23326b8bf05

### 导入导出
sudo docker save -o ~/nginx.tar.gz nginx:1.18

sudo docker load --input nginx.tar.gz