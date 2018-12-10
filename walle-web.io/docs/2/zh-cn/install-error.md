title: 安装错误
---

## Python / Pip
如果是Python或Pip环境安装有问题，请自行百度/google解决。其它问题严格对照手册，一步步来应该不会出现问题

## 其它问题
- [提Issue](https://github.com/meolu/walle-web/issues/new/choose)
- 加微信群，互帮互助
![](/docs/2/zh-cn/static/group-wechat.jpg)

## 数据库连接问题
执行 flask db upgrade 后提示Can`t connect to local MYSQL server through socket "/var/lib/mysql/mysql.sock",可以将mysql.sock做一个软连接，比如你的mysql.sock文件在/usr/local/mysql/mysqld.sock，则执行 ln -s /usr/local/mysql/mysqld.sock /var/lib/mysql/mysql.sock即可
