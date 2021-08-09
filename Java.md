# Instruction







## 第一步 ：安装JDK

- 双击jdk-8u301-macosx-x64.dmg文件执行安装

## 第二步 ： 配置环境

- vim /etc/profile
- JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_301.jdk/Contents/Home/
- JRE_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_301.jdk/Contents/Home/jre
- PATH=$PATH:$JAVA_HOME/bin:$JRE_HOME/bin
- CLASSPATH=.:$JAVA_HOME/lib/dt.jar:$JAVA_HOME/lib/tools.jar:$JRE_HOME/lib
- export JAVA_HOME JRE_HOME PATH CLASSPATH
- source /etc/profile

## 第三步 ： 验证安装配置结果

- 运行CMD，执行下命令
- java -version

## 第四步 ： 显示结果

- java version "1.8.0_301"
- Java(TM) SE Runtime Environment (build 1.8.0_301-b09)
- Java HotSpot(TM) 64-Bit Server VM (build 25.301-b09, mixed mode)
