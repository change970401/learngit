
第一周周报_开源组件健康扫描小组_1901210362_程智雅
1、在learn-with-open-source项目中提交了一个PR，修改了en/Before-start章节的英语语法错误和标题格式的问题，PR地址为：https://github.com/zhuangbiaowei/learn-with-open-source/pull/177  【Merged】
#2、
成为了learn-with-open-source项目的committer，负责英语部分的review和approve
#3、在OS-ABC/HelloWorld项目中，撰写了“提交作业”文档，链接地址：https://github.com/OS-ABC/HelloWorld/blob/master/doc/Homework/1901210362.md

#第二周周报_开源组件健康扫描小组_1901210362_程智雅
#1.作业（后端）—— 利用Springboot 打印出helloWorld +学号
（1）.创建项目
（2）.写Controller
![Image text](https://github.com/change970401/learngit/blob/master/img/图片1.png)
（3）.写SpringbootApplication
![Image text](https://github.com/change970401/learngit/blob/master/img/图片2.png)
（4）.运行结果
![Image text](https://github.com/change970401/learngit/blob/master/img/图片3.png)
![Image text](https://github.com/change970401/learngit/blob/master/img/图片4.png)

#2.开源组件健康扫描小组：暂定扫描Maven文件，扫描pom.xml中的dependency。
学习SpringBoot里的pom.xml文件
pom.xml：Maven构建说明文件
![Image text](https://github.com/change970401/learngit/blob/master/img/5.png)
其中，<parent>...</parent> spring-boot-starter-parent是一个特殊的 starter ，它用来提供相关的 Maven 默认依赖，使用它之后，常用的包依赖就可以省去 version 标签。

关于具体 Spring Boot 提供了哪些 jar 包的依赖，我们可以查看本地 Maven 仓库下：\repository\org\springframework\boot\spring-boot-dependencies\2.0.1.RELEASE\spring-boot-dependencies-2.0.1.RELEASE.pom 文件来查看,打开文件可以看到很多<lombok.version>1.18.4</lombok.version>这样的<包名.version>版本号</包名.version>。
