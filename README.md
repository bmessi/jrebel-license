jdk 17
临时设置
set JAVA_HOME=E:\Program\Java\jdk-17

cd /path/to/project
mvn compile 
mvn exec:java -Dexec.mainClass="com.vvvtimes.server.MainServer" -Dexec.args="-p 8081"
