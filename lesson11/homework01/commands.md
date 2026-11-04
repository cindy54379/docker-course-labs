# 第11讲 作业1：MySQL 容器操作命令

## 1. 查看已有容器
docker ps -a

## 2. 启动 MySQL 容器
docker start mysql-test

## 3. 查看容器运行状态
docker ps

## 4. 查看 MySQL 日志
docker logs -f mysql-test

说明：按 Ctrl+C 结束日志查看。

## 5. 进入 MySQL
docker exec -it mysql-test mysql -uroot -p

## 6. 执行 SQL
SHOW DATABASES;
EXIT;

## 7. 停止 MySQL 容器
docker stop mysql-test

## 8. 参数说明
-e 用于设置容器环境变量。
MYSQL_ROOT_PASSWORD 用于首次初始化时配置 MySQL root 密码。
