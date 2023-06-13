# kivy_buildozer_docker
Docker of buildozer1.2.0 in ubuntu20.04

（1）使用方法：

sudo docker pull dingweijie/ubuntu20_buildozer

基于ubuntu建立的buldozer容器

username:kivy

password:kivy

1)sudo docker run -it --name mybuildozer dingweijie/ubuntu20_buildozer:v1

2)sudo docker exec -it mybuildozer /bin/bash

3)开始使用buildozer

容器内有一个经过打包测试的myapp目录(/home/kivy/src/myapp)，打包其他app可以参考该目录里的buildozer.spec文件，该文件也备份在/home/kivy/tools

（2）容器环境 Docker of buildozer in ubuntu

buildozer: 1.2.0

ubuntu: 20.04

python: 3.8

python-for-android tag: v2021.0905

kivy: 2.0.0

arch: armeabi-v7a

android api: 27

android ndk: 19c

博文： 
https://blog.csdn.net/cloud1980_cn/article/details/131161408
