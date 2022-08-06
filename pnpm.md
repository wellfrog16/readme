# pnpm配置路径

npm install -g pnpm    # 全局安装pnpm
pnpm --version    # pnpm版本
pnpm config set store-dir "D:\.pnpm-store"    # pnpm全局仓库路径(类似 .git 仓库)
pnpm config set global-dir "D:\nodejs\pnpm\pnpm-global"    # pnpm全局安装路径
pnpm config set global-bin-dir "D:\nodejs"    # pnpm全局bin路径
pnpm config set state-dir "D:\nodejs\pnpm"    # pnpm创建pnpm-state.json文件的目录
pnpm config set cache-dir "D:\nodejs\pnpm\cache"    # pnpm全局缓存路径