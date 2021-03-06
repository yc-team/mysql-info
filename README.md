## learn mysql

#### 连接

```
mysql -h主机地址 -u用户名 -p用户密码
```

#### 退出

```
exit
```

#### 显示数据库

显示 mysql 中所有的数据库名称

```
show databases;  
```

#### 使用数据库

```
use test;
```

#### 显示当前数据库中所有的表

```
show tables;
```

也支持模糊查询

```
show tables like 'channel%';
```


#### 查询

1、 count(*)

```
select count(*) from channel;
```

2、 显示指定表的列

```
show columns from channel;
```

3、显示指定表的创建语句

```
show create table channel;
```





#### 显示版本

```
show version();
```


#### 显示当前时间

```
show now();
```

#### 当计算器用

```
select 2+2;
```




## 扩展阅读：

* [MySQL show的实际操作用法](http://database.51cto.com/art/201005/202213.htm)
* [显示MYSQL表信息的方法](http://database.51cto.com/art/201011/234428.htm)