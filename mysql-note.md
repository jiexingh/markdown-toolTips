<!--
 * @Autor: jiexingh
 * @Date: 2020-03-26 00:15:22
 * @LastEditors: jiexingh
 * @LastEditTime: 2020-03-26 00:23:43
 -->

# mysql 学习笔记 命令行的方式

数据库 表 取名规则：通常取 数据库名称前两个字母加下划线  比如: db_user  

+ 数据库启动:

```mysql  
net start mysql
```

+ 数据库关闭:

```mysql
net stop mysql
```

+ 登录数据库:

```mysql
mysql -h[ip/域名] -p端口 -u用户名 -p密码  

//也可直接mysql -u用户名 -p
//之后会直接让你输入密码
```
