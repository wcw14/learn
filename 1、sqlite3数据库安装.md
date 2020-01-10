## 1、sqlite3数据库安装

### 	1）本地安装

​		sudo dpkg -i *.deb

### 	2）在线安装

​		sudo apt-get install-sqlite3

## 2、SQLITE3基本命令

### 	1）系统命令

​		以“.”开头的命令

​		.help 帮助

​		.quit 推出

​		.exit 退出

### 	2）sql命令

​		基本的sql命令，不以‘.’开头，但是都要以‘；’结尾

​		创建一张数据库 stu

​		create table stu(id Integer, name char, score Integer);

​		插入一条记录

​		insert into stu values(1001,'zhangsan',80);

​		insert into stu (name, score)value(1003, 'wangwu');//部分字段插入操作

