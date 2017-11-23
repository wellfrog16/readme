## nginx 安装与配置

``` bash
# 下载
wget -c http://nginx.org/download/nginx-1.12.2.tar.gz

# 解压
tar -zxvf nginx-1.12.2.tar.gz

# 进入解压目录
cd nginx-1.12.2.tar.gz

# 配置
./configure --prefix=/usr/local/nginx
这样安装时系统就会把Nginx安装到/usr/local/nginx目录下。

# 安装
make
make install

```