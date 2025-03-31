# 开发调试
## 出现代码风格检查错误
出现代码风格检查错误可以通过plugins进行检查具体错误位置
idea右侧->Plugins->checkstyle:checkstyle
## 编译
```shell
mvn clean install -DskipTests -Prelease-nacos
```
## 调试
- JVM参数
```shell
-Dnacos.standalone=true 
-Dloader.path=D:/nacos/plugins 
-Dnacos.home=D:/nacos 
-Dlogging.config=D:/workspaces/2.my_project/nacos/distribution/conf/nacos-logback.xml
```
