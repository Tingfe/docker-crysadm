我只是搬运工

此版本增加了自动提现功能

云监工程序docker版，以tutum/ubuntu:trusty为母镜像

适用于所有docker平台

外接卷路径/var/lib/redis，就是redis数据库存放目录

容器端口云监工端口4000 ssh端口22，可以ssh到容器，root密码在日志查找

此云监工源代码提取自 https://gitbhub.com/sanzuwu/crysadm.git

也是我fork自别人，如果有更新，我会更新的

不足之处：服务器时区不是北京时区，不能定时重启云监工，这些都需要ssh或控制台自己实现

