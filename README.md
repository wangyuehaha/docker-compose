# docker-compose
docker-compose.yml仓库

##启动例子
###mysql-redis-nginx-rabbitmq.yml
- 1.mkdir test
- 2.cd test
- 3.docker-compose -f mysql-redis-nginx-rabbitmq.yml up -d
- 4.查看进程
    - docker-compose -f mysql-redis-nginx ps
- 5.查看对应服务的日志
    - docker-compose -f mysql-redis-nginx-rabbitmq.yml logs 【服务名】
    
    
### windows-mysql-redis-nginx-rabbitmq.yml
- windows版本的docker下的yml
- 数据卷映射需要设置