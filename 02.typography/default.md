---
title: Linux
---

### jenkins
visudo 修改jenkins执行bash脚本的权限

jenkins ALL=NOPASSWD: /var/lib/jenkins/script/
jenkins ALL=(ALL) NOPASSWD:ALL


### docker 无响应时
netstat -ntpl//查看服务

ps auxwwf//查看进程树

kill -9 pid//杀死进程 -9 强制

### git 保存密码
git config credential.helper manager

### vim docs

find /usr/share/vim/vim81/doc -name "*.txt" -exec perl /usr/share/vim/vim81/doc/vim2html.pl /usr/share/vim/vim81/doc/tags {} \;
