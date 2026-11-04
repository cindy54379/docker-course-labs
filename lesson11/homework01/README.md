# 作业1：运行 MySQL 容器并连接

## 一、实验目标
使用 Docker 运行 MySQL 8.0 容器，
查看启动日志，连接数据库并执行 SQL。

## 二、实验环境
- 阿里云 ECS
- Ubuntu 22.04
- Docker Engine 29.1.3
- MySQL 8.0 Docker 镜像

## 三、实验步骤
1. 查看已有 MySQL 容器
2. 启动 mysql-test 容器
3. 查看 MySQL 启动日志
4. 进入 MySQL 客户端
5. 执行 SHOW DATABASES
6. 退出并停止容器

## 四、实验结果
MySQL 容器成功启动。
日志显示 ready for connections。
SHOW DATABASES 成功显示数据库列表。

## 五、参数说明
Docker run 中的 -e 参数用于向容器传入环境变量。
例如 MYSQL_ROOT_PASSWORD 可用于首次初始化数据库时设置 root 密码。

## 六、实验总结
掌握了 Docker 容器启动、日志查看、
数据库连接和基本 SQL 查询操作。

## 七、实验截图
截图存放于 screenshots 目录。
