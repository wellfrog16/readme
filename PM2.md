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

pm2 start <js文件路径>.js
pm2 start <json描述文件路径>.json
pm2 start <python文件路径>.py --interpreter python
pm2 start <sh文件路径>.sh --interpreter bash
pm2 start ./node_modules/<某模块名称>/<模块主文件路径>.js
pm2 start <某种方式> -- --param_name param_value
pm2 start npm -- start
pm2 start npm -- run <scriptname>
pm2 start npm --name api -- run dev
pm2 start yarn -- start
pm2 start yarn -- run <scriptname>
pm2 start <某种方式> --watch

pm2 start npm --watch --name <taskname> -- run start

```