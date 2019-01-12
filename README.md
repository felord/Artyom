# ubuntu安装设置
## 1、Ubuntu font install:  
<code>sudo ./install-font-ubuntu.sh https://github.com/felord/Artyom.git/master/Microsoft Yahei Mono.ttf?raw=true
</code>
## 2、ubuntu 镜像源修改：
  <code>sudo cp /etc/apt/sources.list /etc/apt/sources.list.bak</code><br>
<code>sudo vim /etc/apt/sources.list</code><br>
vim中输入以下命令，将源改为阿里
<code>:%s/security.ubuntu/mirrors.aliyun/g</code>
<code>:%s/archive.ubuntu/mirrors.aliyun/g</code>
更新
<code>sudo apt update</code>



