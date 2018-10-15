查询：select * from tablename ;

插入：insert into tablename；

更新 ：update tablename set columnname='' where a=b ；

删除 ： delete from tablename where a=b ；

建表语句： create table tablename (a int; b int);

修改表语句: alter table tablename alter/add/delete columnname; 

其中查询和插入语句直接执行；

更新和删除语句 执行之前 一定要先备份表，其形式为：

例如：update tablename set a='' where b=c ；

	备份： create table tablename_07111639（当前时间 月 日 时 分） as select * from tablename;
	
修改表语句只 执行 添加操作：

例如：alter table tablename add columnname ;
