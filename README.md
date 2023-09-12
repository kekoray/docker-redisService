# docker-redisService
### 版本说明

| 版本         | CPU架构       |
| :----------- | ------------- |
| redis:latest | amd64 / arm64 |



### 目录结构

```shell
docker-redisService/
├── conf
│   └── redis.conf     # 配置文件
├── docker-compose.yml
└── README.md
```



### 配置文件

> redis.conf文件官方下载地址：http://download.redis.io/redis-stable/redis.conf 
>

**1.设置登录密码**

```properties
requirepass <passwd>
```



### 容器操作

```shell
# 连接redis
docker exec -it redis redis-cli

# redis命令行输入密码
auth <passwd>
```