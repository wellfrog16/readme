## nginx 安装

``` bash
# 目录
cd usr/src

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

## 全局环境变量

``` bash
# 修改文件
vim /root/.bash_profile

# 追加（结果类似于 PATH=$PATH:$HOME/bin:/usr/local/nginx/sbin）
:/usr/local/nginx/sbin

```


## 安装错误修复

``` bash
# the HTTP rewrite module requires the PCRE library.
yum install -y pcre-devel

# the HTTP gzip module requires the zlib library.
yum install -y zlib-devel

```

## 命令

```bash
# 启动
nginx

# 停止
nginx -s stop
nginx -s quit

# 重启
nginx -s reload

```