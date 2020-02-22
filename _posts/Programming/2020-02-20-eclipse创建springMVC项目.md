---
layout: post  
title: eclipse&springMVC——创建并运行  
category: programming  
tag: springMVC  
---
## 步骤如下：
- - -
### 1. 创建maven项目
- - -
File->new->other...->maven project->选择存储位置，next->maven-archetype-webapp，next->输入相关信息，finish
![maven project](/public/myimage/eclipse创建springMVC项目-01.png)
![选择位置](/public/myimage/eclipse创建springMVC项目-02.png)
![archetype](/public/myimage/eclipse创建springMVC项目-03.png)
![finish](/public/myimage/eclipse创建springMVC项目-04.png)
- - -
### 2. 添加server library(已配置好tomcat)
- - -
右键项目->Build path->configure Build path...->选中classpath->Add Library...->Server RunTime->Apache Tomcat，finish
![build path](/public/myimage/eclipse创建springMVC项目-05.png)
![server Runtime](/public/myimage/eclipse创建springMVC项目-06.png)
![tomcat](/public/myimage/eclipse创建springMVC项目-07.png)
![finish](/public/myimage/eclipse创建springMVC项目-08.png)
![目录](/public/myimage/eclipse创建springMVC项目-09.png)
- - -
### 3. 写上spring mvc相关代码和xml配置文件（省略）
- - -
### 4. 部署&运行
- - -
右键项目->Properties->Project Facets->Convert to faceted from...->选择Dynamic Web Module，apply and close->删除WebContent文件夹
->右键项目->Properties->Deployment Assembly->删除/WebContent这一项->add,folder,next->选择src/main/webapp，finish->Run as->Run on server
->浏览器输入网址
![covert](/public/myimage/eclipse创建springMVC项目-10.png)
![dynamic web module](/public/myimage/eclipse创建springMVC项目-11.png)
![folder](/public/myimage/eclipse创建springMVC项目-12.png)
![webapp](/public/myimage/eclipse创建springMVC项目-13.png)
![finish](/public/myimage/eclipse创建springMVC项目-14.png)