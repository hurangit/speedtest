# Speedtest
LibreSpeed，轻量级的Speedtest，基于HTML和Javascript。

# 原项目地址
https://github.com/librespeed/speedtest
# 系统要求
Ubuntu19.04+
# 1.安装环境
### 更新软件
sudo apt update
### 安装git命令
apt install git
### 安装php
sudo apt install apache2 php
# 2.部署测速服务
### 1.git命令
git clone https://github.com/hurangit/speedtest.git
### 2.移动到文件夹
cd speedtest
### 3.复制文件到www目录下
sudo cp -R backend progress.html *.js /var/www/html/
### 4.更改文件名为index.html
cd /var/www/html/

sudo mv progress.html index.html
### 6.更改权限
sudo chown -R www-data *
# 3开始测试
浏览器输入你IP地址开始测试速度
