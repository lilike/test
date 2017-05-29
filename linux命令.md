## 第一台Linux:
### 1. dubbo注册中心zookeeper:
1. /usr/local/dubbo-zookeeper/bin/zkServer.sh start
2. /usr/local/dubbo-zookeeper/bin/zkServer.sh status
3. /usr/local/dubbo-zookeeper/bin/zkServer.sh restart
4. /usr/local/dubbo-zookeeper/bin/zkServer.sh stop
5. ps -ef | grep zookeeper: 查看所有的进程再过滤指定的名称的进程

### 2. dubbo监控中心Monitor:
1. /usr/local/web/tomcat-dubbo-monitor/bin/startup.sh
2. /usr/local/web/tomcat-dubbo-monitor/bin/shutdown.sh
3. ps -ef | grep tomcat
4. kill -9 进程号
5. http://192.168.12.128:8080


### 3. FastDFS启动的命令：(设置了开机自动启动)
   a. 追踪服务器(自动启动)：
      /usr/bin/fdfs_trackerd /etc/fdfs/tracker.conf restart

   b. 存储服务器(自动启动)：
      /usr/bin/fdfs_storaged /etc/fdfs/storage.conf restart

   c. nginx启动：
      /usr/local/nginx/sbin/nginx
   d. 进程中查看
	   ps -ef | grep fdfs


### 4. Redis单机版启动命令：

   cd /usr/local/redis/bin
   ./redis-server redis.conf


### 5. Redis集群版启动命令：
   /usr/local/redis/redis-cluster/start-all.sh
  
### 6. git push
   /使用git push 可以将本地的代码直接提交到远程的仓库,信不信










