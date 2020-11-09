# runit
runit是一个应用（application）启动管理工具。通过Procfile文件启动相应的进程。

Usage: runit [-c] [-f procfile|Procfile] [-e envfile|.env]

- runit 启动Procfile中的所有进程
- runit -f procfile -e env_file
- runit -c 检查Procfile, env_file文件格式的正确性
- runit -h 打印帮助

# 运行一个典型的Procfile
make run
