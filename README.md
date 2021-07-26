# v2rayOnUbuntu
how to use v2raya with UI on Ubuntu16.04

## 安装v2ray
```
# download script
curl -O https://cdn.jsdelivr.net/gh/v2rayA/v2rayA@master/install/go.sh
# install v2ray-core from jsdelivr
sudo bash go.sh
```
- 第一步之后可能要把输出复制到新建文件go.sh中，修改文件属性为可执行。
- 此镜像为v2rayA提供的镜像，能够兼容，官方安装会导致not found

## 安装v2rayA
```
wget -qO - https://apt.v2raya.mzz.pub/key/public-key.asc | sudo apt-key add -
echo "deb https://apt.v2raya.mzz.pub/ v2raya main" | sudo tee /etc/apt/sources.list.d/v2raya.list
sudo apt update
sudo apt install v2rayA
```
## 参考
```
https://github.com/v2rayA/v2rayA/wiki/%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95
```

