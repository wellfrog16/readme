## PM2 安装

``` bash

npm install -g pm2

```


## PM2 命令

``` bash

pm2 list                            # 显示所有进程状态
pm2 list --force                    # 显示所有进程详细状态
pm2 show id                         # 显示指定进程详情
pm2 start app.js --name serverone   # 启动一个进程并把它命名为 serverone
pm2 restart servername              # 重启指定的进程
pm2 stop servername                 # 停止一个进程

```