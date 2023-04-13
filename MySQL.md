# —==基础篇==—

# SQL

## DDL

### DDL-数据库操作

![image-20230324203357741](MySQL.assets/image-20230324203357741.png)



### DDL-表操作

#### 查询

![image-20230324204748362](MySQL.assets/image-20230324204748362.png)



#### 创建

![image-20230324204833583](MySQL.assets/image-20230324204833583.png)

#### 数据类型

##### 数值类型

![image-20230324205913537](MySQL.assets/image-20230324205913537.png)



##### 字符串类型

![image-20230324205926638](MySQL.assets/image-20230324205926638.png)



##### 日期类型

![image-20230324210001434](MySQL.assets/image-20230324210001434.png)



#### 修改

![image-20230324211528869](MySQL.assets/image-20230324211528869.png)

![image-20230324211756557](MySQL.assets/image-20230324211756557.png)

![image-20230324211915357](MySQL.assets/image-20230324211915357.png)

![image-20230324212106254](MySQL.assets/image-20230324212106254.png)

![image-20230324212531120](MySQL.assets/image-20230324212531120.png)



### MySQL图形化界面

![image-20230324212917885](MySQL.assets/image-20230324212917885.png)



## DML

### 添加数据-insert

![image-20230327211719068](MySQL.assets/image-20230327211719068.png)



### 修改数据-update

![image-20230327213615300](MySQL.assets/image-20230327213615300.png)

### 删除数据-delete

![image-20230327214340341](MySQL.assets/image-20230327214340341.png)	



## DQL

### 语法

+ 编写顺序

![image-20230327220100801](MySQL.assets/image-20230327220100801.png)



### 基本查询

![image-20230327220228434](MySQL.assets/image-20230327220228434.png)

### 条件查询-WHERE

![image-20230327220751570](MySQL.assets/image-20230327220751570.png)





### 聚合函数

![image-20230327221704196](MySQL.assets/image-20230327221704196.png)





### 分组查询-GROUP BY

![image-20230327222641299](MySQL.assets/image-20230327222641299.png)



### 排序查询-ORDER BY

![image-20230327223053789](MySQL.assets/image-20230327223053789.png)





### 分页查询-LIMIT

![image-20230327223356396](MySQL.assets/image-20230327223356396.png)



### 执行顺序

![image-20230327224835996](MySQL.assets/image-20230327224835996.png)







## DCL

### 管理用户

![image-20230327230625451](MySQL.assets/image-20230327230625451.png)



### 权限控制

![image-20230327230940761](MySQL.assets/image-20230327230940761.png)

![image-20230327231519634](MySQL.assets/image-20230327231519634.png)



# 函数

## 字符串函数

![image-20230328215307860](MySQL.assets/image-20230328215307860.png)

![image-20230328221057895](MySQL.assets/image-20230328221057895.png)





## 数值函数

![image-20230328221015308](MySQL.assets/image-20230328221015308.png)

![image-20230328221028802](MySQL.assets/image-20230328221028802.png)



## 日期函数

![image-20230328220958080](MySQL.assets/image-20230328220958080.png)

## 流程函数

![image-20230328222238644](MySQL.assets/image-20230328222238644.png)





# 约束

## 概述

![image-20230328223655749](MySQL.assets/image-20230328223655749.png)

## 演示

+ auto_increment

![image-20230328224819845](MySQL.assets/image-20230328224819845.png)

![image-20230328230139349](MySQL.assets/image-20230328230139349.png)





## 外键约束

![image-20230328230321365](MySQL.assets/image-20230328230321365.png)

### 语法

![image-20230328231207378](MySQL.assets/image-20230328231207378.png)



### 删除/更新行为

![image-20230328231728965](MySQL.assets/image-20230328231728965.png)





# 多表查询

## 多表关系

### 概述

![image-20230329193608908](MySQL.assets/image-20230329193608908.png)

### 一对多（多对一）

![image-20230329193701288](MySQL.assets/image-20230329193701288.png)



### 多对多

![image-20230329193807535](MySQL.assets/image-20230329193807535.png)





### 一对一

+ 单表拆分

![image-20230329194148240](MySQL.assets/image-20230329194148240.png)



## 多表查询概述

### 概述

![image-20230329194735019](MySQL.assets/image-20230329194735019.png)

### 多表查询分类

![image-20230329195037622](MySQL.assets/image-20230329195037622.png)



## 内连接

### 语法

![image-20230329195559376](MySQL.assets/image-20230329195559376.png)

### 案例

![image-20230329200702073](MySQL.assets/image-20230329200702073.png)



## 外连接

+ 连接起来的数据就是交集

### 语法

![image-20230329200030067](MySQL.assets/image-20230329200030067.png)

### 案例

![image-20230329200831573](MySQL.assets/image-20230329200831573.png)





## 自连接

### 解释

![image-20230329200311395](MySQL.assets/image-20230329200311395.png)



### 语法

+ 起别名
  + +内连接查询
  + +外连接查询



### 案例

![image-20230329200610400](MySQL.assets/image-20230329200610400.png)





## 联合查询-union，union all

### 语法

![image-20230329201554934](MySQL.assets/image-20230329201554934.png)

+ 放到where and？？

### 案例

![image-20230329201458450](MySQL.assets/image-20230329201458450.png)







## 子查询

### 概念

![image-20230329201828624](MySQL.assets/image-20230329201828624.png)



### 标量子查询

![image-20230329202325650](MySQL.assets/image-20230329202325650.png)		



### 列子查询

![image-20230329203143199](MySQL.assets/image-20230329203143199.png)



### 行子查询

![image-20230329203640797](MySQL.assets/image-20230329203640797.png)

![image-20230329203529712](MySQL.assets/image-20230329203529712.png)



### 表子查询

![image-20230329204413278](MySQL.assets/image-20230329204413278.png)

![image-20230329204355526](MySQL.assets/image-20230329204355526.png)





## 多表查询案例

![image-20230329214333364](MySQL.assets/image-20230329214333364.png)



# 事务

## 事务简介

![image-20230330215832010](MySQL.assets/image-20230330215832010.png)



## 事务操作

### 方式一

![image-20230330220750338](MySQL.assets/image-20230330220750338.png)

<img src="MySQL.assets/image-20230330220816287.png" alt="image-20230330220816287" style="zoom:50%;" />





### 方式二

![image-20230330221103526](MySQL.assets/image-20230330221103526.png)

<img src="MySQL.assets/image-20230330221046516.png" alt="image-20230330221046516" style="zoom:50%;" />



## 事务的四大特性

+ 原子性、一致性、隔离性、持久性(ACID)

![image-20230330221706198](MySQL.assets/image-20230330221706198.png)



## 并发事务问题

### 脏读

![image-20230330222314014](MySQL.assets/image-20230330222314014.png)

![image-20230330222324250](MySQL.assets/image-20230330222324250.png)



### 不可重复读

![image-20230330222347442](MySQL.assets/image-20230330222347442.png)

![image-20230330222412802](MySQL.assets/image-20230330222412802.png)



### 幻读

![image-20230330222429085](MySQL.assets/image-20230330222429085.png)

![image-20230330222450329](MySQL.assets/image-20230330222450329.png)





## 事务的隔离级别-解决上述问题

## 事务隔离级别

![image-20230330223911400](MySQL.assets/image-20230330223911400.png)

+ Repeatable Read
  + 可重复读
+ Serializable
  + 串行化



# —==进阶篇==—



# 存储引擎

## MySQL体系结构

![image-20230410155215672](MySQL.assets/image-20230410155215672.png)



## 存储引擎简介

![image-20230410160113704](MySQL.assets/image-20230410160113704.png)

+ 指定存储引擎

![image-20230410160400489](MySQL.assets/image-20230410160400489.png)



## 存储引擎特点

![image-20230410160822162](MySQL.assets/image-20230410160822162.png)

+ MyISAM

![image-20230410161543279](MySQL.assets/image-20230410161543279.png)

+ Memory

![image-20230410161639930](MySQL.assets/image-20230410161639930.png)

+ 区别
  + InnoDB与MyISAM的区别：==**事务，外键，行级锁**==

![image-20230410161818780](MySQL.assets/image-20230410161818780.png)



## InnoDB逻辑存储结构

![image-20230410161325634](MySQL.assets/image-20230410161325634.png)



## 存储引擎选择

![image-20230410162057561](MySQL.assets/image-20230410162057561.png)



# 索引

## 索引概述

![image-20230410175748776](MySQL.assets/image-20230410175748776.png)

+ 优缺点

![image-20230410180358440](MySQL.assets/image-20230410180358440.png)



## 索引结构

### 索引结构

![image-20230410180601877](MySQL.assets/image-20230410180601877.png)

### 数据库支持

![image-20230410180721301](MySQL.assets/image-20230410180721301.png)



### 二叉树

![image-20230410185103158](MySQL.assets/image-20230410185103158.png)

### B-Tree

![image-20230410185525020](MySQL.assets/image-20230410185525020.png)



### B+-Tree

![image-20230410190020819](MySQL.assets/image-20230410190020819.png)

![image-20230410190158988](MySQL.assets/image-20230410190158988.png)

+ ### mysql中的B+Tree

![image-20230410190411492](MySQL.assets/image-20230410190411492.png)



### Hash

![image-20230410190630228](MySQL.assets/image-20230410190630228.png)

![image-20230410190736737](MySQL.assets/image-20230410190736737.png)



### 思考：为什么InnoDB存储引擎选择使用B+tree

![image-20230410191007889](MySQL.assets/image-20230410191007889.png)





## 索引分类

### 分类

![image-20230410191432748](MySQL.assets/image-20230410191432748.png)



### 在InnoDB存储引擎中

+ 聚集索引
+ 二级索引

![image-20230410191644407](MySQL.assets/image-20230410191644407.png)

![image-20230410191818338](MySQL.assets/image-20230410191818338.png)





### 回表查询

![image-20230410191958651](MySQL.assets/image-20230410191958651.png)



### 思考：InnoDB主键索引的B+tree高度为多高

<img src="MySQL.assets/image-20230410192752339.png" alt="image-20230410192752339" style="zoom:50%;" />



## 索引语法

### 语法

![image-20230410192945873](MySQL.assets/image-20230410192945873.png)



### 案例

![image-20230410194327256](MySQL.assets/image-20230410194327256.png)



## SQL性能分析

### 查看SQL的执行频次

![image-20230411110849997](MySQL.assets/image-20230411110849997.png)



### 慢查询日志

![image-20230411112105822](MySQL.assets/image-20230411112105822.png)

### 	profile详情

![image-20230411121014460](MySQL.assets/image-20230411121014460.png)



### explain执行计划

![image-20230411121220855](MySQL.assets/image-20230411121220855.png)

![image-20230411122717210](MySQL.assets/image-20230411122717210.png)

![image-20230411123021066](MySQL.assets/image-20230411123021066.png)



## 索引使用规则

### 验证索引效率

![image-20230411164240186](MySQL.assets/image-20230411164240186.png)



### 最左前缀法则-联合索引

![image-20230411164813456](MySQL.assets/image-20230411164813456.png)



### 范围查询

![image-20230411165007433](MySQL.assets/image-20230411165007433.png)

### 索引失效情况一

#### 索引列运算

![image-20230411165355974](MySQL.assets/image-20230411165355974.png)

#### 字符串不加单引号

![image-20230411165549374](MySQL.assets/image-20230411165549374.png)

#### 模糊查询

![image-20230411165732292](MySQL.assets/image-20230411165732292.png)



### 索引失效情况二

#### or连接的条件

![image-20230411170046513](MySQL.assets/image-20230411170046513.png)

#### 数据分布影响

![image-20230411170533306](MySQL.assets/image-20230411170533306.png)



### SQL提示

![image-20230411171143472](MySQL.assets/image-20230411171143472.png)





### 覆盖索引&回表查询

+ 查询展示的字段在二级索引中都有不需要回表查询

![image-20230411172510183](MySQL.assets/image-20230411172510183.png)



![image-20230411172536552](MySQL.assets/image-20230411172536552.png)

#### 思考

![image-20230411172620811](MySQL.assets/image-20230411172620811.png)

+ 对username，password建立联合索引





### 前缀索引

![image-20230411181458443](MySQL.assets/image-20230411181458443.png)

![image-20230411181755951](MySQL.assets/image-20230411181755951.png)



### 单列&联合索引

![image-20230411182147455](MySQL.assets/image-20230411182147455.png)

![image-20230411182303760](MySQL.assets/image-20230411182303760.png)





## 索引设计原则

![image-20230411183120771](MySQL.assets/image-20230411183120771.png)







# SQL优化



## 插入数据

### insert优化-批量插入

+ 批量插入、手动提交事务、主键顺序插入

![image-20230412192852718](MySQL.assets/image-20230412192852718.png)



### 大批量插入数据

![image-20230412194111435](MySQL.assets/image-20230412194111435.png)



## 主键优化

### 数据组织方式

![image-20230412194347795](MySQL.assets/image-20230412194347795.png)

![image-20230412194410128](MySQL.assets/image-20230412194410128.png)

### 主键乱序==插入==会出先==页分裂==

![image-20230412194650226](MySQL.assets/image-20230412194650226.png)

### ==删除==时会出现==页合并==

![image-20230412194848674](MySQL.assets/image-20230412194848674.png)



### 主键设计原则

![image-20230412195231586](MySQL.assets/image-20230412195231586.png)

## order by优化

![image-20230412200056847](MySQL.assets/image-20230412200056847.png)

![image-20230412200212488](MySQL.assets/image-20230412200212488.png)





## group by优化

![image-20230412200656094](MySQL.assets/image-20230412200656094.png)



## limit优化

![image-20230412201442068](MySQL.assets/image-20230412201442068.png)





## count优化

### 优化思路

![image-20230412201708895](MySQL.assets/image-20230412201708895.png)

### count的几种用法及效率

![image-20230412202143012](MySQL.assets/image-20230412202143012.png)

![image-20230412202325761](MySQL.assets/image-20230412202325761.png)





## update优化

+ InooDB中用索引行锁，反之表锁

![image-20230412203322640](MySQL.assets/image-20230412203322640.png)







# 视图-view

## 介绍

![image-20230412210803820](MySQL.assets/image-20230412210803820.png)

## 视图创建，查询，修改，删除

![image-20230412211534987](MySQL.assets/image-20230412211534987.png)



## 视图的检查选项 cascaded/local

+ cascaded：级联
  + 会将上层依赖的视图都加上with cascaded check option；

![image-20230412212525743](MySQL.assets/image-20230412212525743.png)

+ local
  + 不会将上层依赖的视图加with local check option; 但是会检查上层（是否有选择选项等）

![image-20230412212710748](MySQL.assets/image-20230412212710748.png)



## 视图的更新

![image-20230412213322542](MySQL.assets/image-20230412213322542.png)

## 视图的作用

![image-20230412213614608](MySQL.assets/image-20230412213614608.png)

+ 数据独立
  + 若基表中列改名了，可以如下图保证视图的列名不变

![image-20230412213722313](MySQL.assets/image-20230412213722313.png)



## 案例

![image-20230412213941942](MySQL.assets/image-20230412213941942.png)



# 存储过程-procedure

## 介绍&特点&基本语法

+ 事先定义并存储在数据库中的一段SQL逻辑

![image-20230413100655318](MySQL.assets/image-20230413100655318.png)

+ 特点
  + 封装，复用
  + 可以接收参数，也可以返回数据
  + 减少网络交互，效率提升

![image-20230413101339267](MySQL.assets/image-20230413101339267.png)

![image-20230413102738514](MySQL.assets/image-20230413102738514.png)

![image-20230413102942830](MySQL.assets/image-20230413102942830.png)



## 流程控制

### 变量

#### 系统变量

![image-20230413105239386](MySQL.assets/image-20230413105239386.png)





#### 用户定义变量

![image-20230413105631063](MySQL.assets/image-20230413105631063.png)





#### 局部变量

![image-20230413110116909](MySQL.assets/image-20230413110116909.png)

+ #### 用 := 赋值



### if判断

![image-20230413110524209](MySQL.assets/image-20230413110524209.png)

### 参数

![image-20230413110703856](MySQL.assets/image-20230413110703856.png)

![image-20230413111625637](MySQL.assets/image-20230413111625637.png)



### case

+ 与流程控制中的函数类似
+ 语法一和switch类似
+ 语法二和if else类似

![image-20230413112220372](MySQL.assets/image-20230413112220372.png)

+ **练习**

![image-20230413113346975](MySQL.assets/image-20230413113346975.png)



### 循环

#### while

![image-20230413162245968](MySQL.assets/image-20230413162245968.png)

![image-20230413163953316](MySQL.assets/image-20230413163953316.png)





#### repeat

+ 满足条件则退出循环

+ 先判断一次在进行循环

![image-20230413162327031](MySQL.assets/image-20230413162327031.png)

![image-20230413163951475](MySQL.assets/image-20230413163951475.png)





#### loop

![image-20230413163019711](MySQL.assets/image-20230413163019711.png)

![image-20230413163944328](MySQL.assets/image-20230413163944328.png)





### 游标cursor

+ 局部变量不能接收一个表的内容
+ 游标可以存储查询结果集

![image-20230413164250669](MySQL.assets/image-20230413164250669.png)

![image-20230413165004949](MySQL.assets/image-20230413165004949.png)

<img src="MySQL.assets/image-20230413165244102.png" alt="image-20230413165244102" style="zoom:50%;" />



#### 条件处理程序handler

+ 配合游标cursor使用

![image-20230413165444349](MySQL.assets/image-20230413165444349.png)

<img src="MySQL.assets/image-20230413165832243.png" alt="image-20230413165832243" style="zoom:50%;" />

<img src="MySQL.assets/image-20230413165905165.png" alt="image-20230413165905165" style="zoom:50%;" />



## 存储函数

> 有返回的存储过程，参数类型只能是in

+ 比较少用
  + 因为存储函数能做的事情存储过程也能做，而且存储函数需要返回值

![image-20230413170133512](MySQL.assets/image-20230413170133512.png)



# 触发器-trigger

## 介绍

+ 可以确保数据完整性、日志记录、数据检验

<img src="MySQL.assets/image-20230413171240665.png" alt="image-20230413171240665" style="zoom:67%;" />

+ 行级触发器表示操作了某行而触发
+ 语句触发器表示执行了某条语句，例如update而触发



## 语法

![image-20230413171557581](MySQL.assets/image-20230413171557581.png)



## 案例

+ **通过触发器记录表的变更日志**

![image-20230413172217154](MySQL.assets/image-20230413172217154.png)

### 插入触发器

![image-20230413172626101](MySQL.assets/image-20230413172626101.png)

### 修改触发器

![image-20230413172928603](MySQL.assets/image-20230413172928603.png)

### 删除触发器

![image-20230413173259613](MySQL.assets/image-20230413173259613.png)







# 锁--5

12





# InnoDB引擎--6

15





# MySQL管理--6

4









# END