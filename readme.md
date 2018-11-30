**使用dcoker-compose构建**
```bash
#启动
docker-compose up
#启动后台启动
docker-compose up -d
#运行状态
docker-compose ps
#其它基本操作
docker-compose stop nginx
docker-compose rm nginx
```


# elasticsearch 

**将数据挂载到宿主机，要求文件的所属用户和用户组为1000 详情看文档**

https://github.com/elastic/elasticsearch-docker/blob/016bcc9db1dd97ecd0ff60c1290e7fa9142f8ddd/templates/Dockerfile.j2#L22

