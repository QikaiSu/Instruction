

# JDK







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
<img width="1016" alt="WeChate76861f08bdb2840637b2fd6c9349125" src="https://user-images.githubusercontent.com/64019119/128669441-2e35cde9-052a-4574-9065-ebb818f162b2.png">

- java version "1.8.0_301"
- Java(TM) SE Runtime Environment (build 1.8.0_301-b09)
- Java HotSpot(TM) 64-Bit Server VM (build 25.301-b09, mixed mode)



# IDE

## 第一步 ：安装IDE
- 执行： spring-tool-suite-4-4.8.0.RELEASE-e4.15.0-macosx.cocoa.x86_64.dmg

## 第二步 ：IDE启动优化
- 编辑 SpringToolSuite4.ini，更新：
- -Xms2048m
- -Xmx2048m
- -XX:+UseG1GC
- -XX:MaxGCPauseMillis=100 
- -XX:GCPauseIntervalMillis=500
- -XX:MetaspaceSize=512M 
- -Xverify:none
- -XX:+DisableExplicitGC
- -XX:-UseBiasedLocking


# Git客户端

## 第一步 ：Git客户端
- https://git-scm.com/download/mac
## 第二步 ：brew install 
- brew install git
- brew install git-gui

<img width="1134" alt="WeChat380e1d0a8f8bed0453ab360fd3955e43" src="https://user-images.githubusercontent.com/64019119/128669564-2a5d590f-2654-4adc-888e-b65fd838d458.png">
