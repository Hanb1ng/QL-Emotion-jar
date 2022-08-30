# QL-Emotion-jar
运行教程

# 1.拉取项目

- 初次拉取 请用  https://raw.githubusercontent.com/fengxiaoruia/QL-Emotion-jar/main/QL-Emotion.jar
- 更新请用 https://raw.githubusercontent.com/fengxiaoruia/QL-Emotion-jar/main/QL-Emotion.jar -O QL-Emotion.jar

# 2.配置完成后在QL-Emotion.jar目录下

- 启动jar包 java -jar QL-Emotion.jar -- server.port=8080(自己换端口)

- 静默运行:nohup java -jar QL-Emotion.jar -- server.port=8080 > log.out 2>&1 &

- 终止服务 ps -ef 查看QL-Emotion.jar的进程号 通过kill pid 杀掉
  结束8080端口进程: sudo fuser -k 8080/tcp

- log.out为日志文件 在jar包同级目录 出BUG了可以把这个日志私发我



