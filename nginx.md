## nginx 安装与配置

``` bash
# 下载
wget -c http://nginx.org/download/nginx-1.12.2.tar.gz

# 解压
tar -zxvf nginx-1.12.2.tar.gz

# 进入解压目录
cd nginx-1.12.2.tar.gz

# 配置（这样安装时系统就会把Nginx安装到/usr/local/nginx目录下。）
./configure --prefix=/usr/local/nginx

# 安装
make
make install

```

## 安装错误修复

``` bash
# the HTTP rewrite module requires the PCRE library.
 yum install -y pcre-devel

# the HTTP gzip module requires the zlib library.
 yum install -y zlib-devel

```