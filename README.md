# QL-Emotion-jar
运行教程

# 1.拉取项目

- 初次拉取 请用  https://raw.githubusercontent.com/fengxiaoruia/QL-Emotion-jar/main/QL-Emotion.jar
- 更新请用 https://raw.githubusercontent.com/fengxiaoruia/QL-Emotion-jar/main/QL-Emotion.jar -O QL-Emotion.jar



# 2. 创建数据库

     - 在宝塔面板数据库选项里创建数据库名为emotion的数据库 账号密码可随意更改 记住这个账号密码

# 3.配置完成后在QL-Emotion.jar目录下

- 启动jar包 java -jar QL-Emotion.jar --server.port=8080(自己换端口)

- 静默运行:nohup java -jar QL-Emotion.jar --server.port=8080 > log.out 2>&1 &

- 终止服务 ps -ef 查看QL-Emotion.jar的进程号 通过kill pid 杀掉
  结束8080端口进程: sudo fuser -k 8080/tcp

- log.out为日志文件 在jar包同级目录 出BUG了可以把这个日志私发我

# 4. 配置资产查询

* 资产查询为单独配置 你可以把这个资产查询部署到任何你想部署的地方 非常灵活 也可以互相调用 缓解了叼毛疯狂查询时服务器压力问题
* 考虑到每个人使用的系统不一样 这里会放几个 常用系统的exe可执行文件 若没有则可以下载源码 自行选择node部署还是打包成相应的格式
* 查询系统架构 uname -m

# 5. 最后在机器人设置资产查询接口即可



