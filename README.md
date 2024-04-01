# 以下是自走人形的搭建教程
按步骤一步步操作即可
## 环境要求
Ubuntu>=16.04 / Debian>=9 （已在该环境下通过测试，系统低于此版本不代表无法安装）
Python>=3.8
Python 版本查询： Python3 -V
如版本低于 3.8 请自行搜索教程更新 Python 版本。
本人用Debian 11搭建（经过实践证明，以下搭建方法和Ubuntu的通用）

## 推荐工具
点击链接下载（自行安装即可）
[xshell 7](https://cdn.netsarang.net/v7/Xshell-latest-p)
[XFTP 7](https://cdn.netsarang.net/v7/Xftp-latest-p)
## 连接服务端
![image](https://github.com/ByteWarlord/PagerMaid-Pyro/assets/156203171/b4b79ad0-7c53-41b7-b8bc-4de61b62a9bb)
![image](https://github.com/ByteWarlord/PagerMaid-Pyro/assets/156203171/181c3220-c1fe-4cf5-aa4f-65b06070487c)
![image](https://github.com/ByteWarlord/PagerMaid-Pyro/assets/156203171/6d0c4a90-e5bb-4c2a-9af7-b53201350c5c)
![image](https://github.com/ByteWarlord/PagerMaid-Pyro/assets/156203171/755c44c3-0d42-4dc0-a328-621ac71d78c4)
## 安装git
复制命令，按enter开始下载git   
`sudo apt update`
`sudo apt install git` 
这是安装成功后的图片

![image](https://github.com/ByteWarlord/PagerMaid-Pyro/assets/156203171/e68bdd7b-3e60-49f4-b1fa-b203e0d966d2)
## 拉取项目
进入/var/lib路径下`cd /var/lib`

拉取项目到该目录下，并命名为papyro1 

`git clone https://github.com/TeamPGM/PagerMaid-Pyro.git papyro1 && cd papyro1`
## 安装软件包
更新 apt 包
`sudo apt update && sudo apt upgrade -y`

`sudo apt install python3-pip python3-venv imagemagick libwebp-dev neofetch libzbar-dev libxml2-dev libxslt-dev tesseract-ocr tesseract-ocr-all -y`

启用虚拟环境 `python3 -m venv venv` `source venv/bin/activate`

更新一下 pip`python3 -m pip install --upgrade pip`

安装 Python 依赖包 `pip3 install -r requirements.txt`

重新进入虚拟环境`source venv/bin/activate`
## 申请Telegram API
进入官网 https://my.telegram.org/
![image](https://github.com/ByteWarlord/PagerMaid-Pyro/assets/156203171/da36ed10-24d7-48a4-b01b-c668224384d5)
![image](https://github.com/ByteWarlord/PagerMaid-Pyro/assets/156203171/e71f0c2c-340a-4545-98a8-28c0d76c2025)
![image](https://github.com/ByteWarlord/PagerMaid-Pyro/assets/156203171/fb5af6c4-326b-4c76-83bd-12b423256474)

## 修改配置文件

## 登录账号


