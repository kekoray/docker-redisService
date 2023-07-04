# docker-redisService
 Docker-compose build program with portainer.


#### redis.conf
redis.conf文件官方下载地址：http://download.redis.io/redis-stable/redis.conf 



### 容器操作

```shell
# 连接redis
docker exec -it redis redis-cli

# redis命令行输入密码
auth <passwd>
```