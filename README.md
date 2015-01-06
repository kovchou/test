### GITHUB使用指南

 - 安装eclipse插件EGit，或者直接使用eclipse的luna版本（该版本自带EGit插件）
 
 - 安装git程序
 
 - 在本地新建目录，比如D:/github，进入到该目录中，在当前目录打开git命令行
  在命令行执行:
  
  ```  
  git clone http://rnd-github.huawei.com/z00229725/TopoComponent
  ```
  
  执行该命令是为了从github上迁出TopoComponent到本地。
 - 打开eclipse，制定workspace为D:\github\TopoComponent
 
 - 在eclipse中配置EGit
 
 - 在eclipse中配置tomcat
 
到此Topo组件的代码在本地搭建完成。
 
##### 1. 推送远程仓库  
克隆服务器端仓库后，会在本地建立一个一样的仓库，称本地仓库。在本地进行commit操作将把更新提交到本地仓库，然后可以将服务器端的更新pull到本地仓库进行合并，最后将合并好的本地仓库push到服务器端，这样就进行了一次远程提交。
(img/push.gif)[img/push.gif]
