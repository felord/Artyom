# ubuntu安装设置
## 1、Ubuntu font install:  
<code>sudo ./install-font-ubuntu.sh https://github.com/felord/Artyom.git/master/Microsoft Yahei Mono.ttf?raw=true
</code>
## 2、ubuntu 镜像源修改：
  <code>sudo cp /etc/apt/sources.list /etc/apt/sources.list.bak</code><br>
<code>sudo vim /etc/apt/sources.list</code><br>
每一版内容不同的地方就是版本号（或者官方一点的说：系统代号）<br>
用<code>lsb_release -c</code>获得<br>
18.04的Ubuntu系统代号为bionic,镜像源就为bionic<br>
  <code>deb https://mirrors.ustc.edu.cn/ubuntu/ bionic main restricted universe multiverse  
  deb-src https://mirrors.ustc.edu.cn/ubuntu/ bionic main restricted universe multiverse  
  deb https://mirrors.ustc.edu.cn/ubuntu/ bionic-updates main restricted universe multiverse  
  deb-src https://mirrors.ustc.edu.cn/ubuntu/ bionic-updates main restricted universe multiverse  
  deb https://mirrors.ustc.edu.cn/ubuntu/ bionic-backports main restricted universe multiverse  
  deb-src https://mirrors.ustc.edu.cn/ubuntu/ bionic-backports main restricted universe multiverse  
  deb https://mirrors.ustc.edu.cn/ubuntu/ bionic-security main restricted universe multiverse  
  deb-src https://mirrors.ustc.edu.cn/ubuntu/ bionic-security main restricted universe multiverse  
  deb https://mirrors.ustc.edu.cn/ubuntu/ bionic-proposed main restricted universe multiverse  
  deb-src https://mirrors.ustc.edu.cn/ubuntu/ bionic-proposed main restricted universe multiverse</code>



