# 工具记录
rocketmq-dashboard-1.0.0.jar
源码路径为:https://github.com/apache/rocketmq-dashboard/releases/tag/rocketmq-dashboard-1.0.0
我这里只做了编译处理，下载后需要修改相应的配置文件使用
简单使用的话只需修改application.properties文件中这三行配置文件
server.port=28080   #默认是8080 根据业务需求自行调整
rocketmq.config.namesrvAddr=10.1.3.232:9876  #需要手动添加rocketmq服务地址以及端口
rocketmq.config.dataPath=/tmp/rocketmq-console/data #根据业务需求自行调整
