# Linux目录结构

**在Linux世界里，一切皆文件**



<img src="LINUX.assets/image-20230310164516872.png" alt="image-20230310164516872" style="zoom:200%;" />



<img src="LINUX.assets/image-20230310162737815.png" alt="image-20230310162737815"  />

<img src="LINUX.assets/image-20230310163105171.png" alt="image-20230310163105171"  />

![image-20230310163541388](LINUX.assets/image-20230310163541388.png)

![image-20230310164222893](LINUX.assets/image-20230310164222893.png)



# 远程登陆Linux

## Xshell

> 只能对远程Linux系统进行命令的操作

![image-20230310165658949](LINUX.assets/image-20230310165658949.png)

![image-20230310165754894](LINUX.assets/image-20230310165754894.png)



## Xftp

![image-20230310172626067](LINUX.assets/image-20230310172626067.png)

![image-20230310172822256](LINUX.assets/image-20230310172822256.png)



# vim快捷键

![image-20230311000018587](LINUX.assets/image-20230311000018587.png)



# 关机&重启命令

+ shutdown

![image-20230311220618530](LINUX.assets/image-20230311220618530.png)





# 登陆注销

![image-20230311221326848](LINUX.assets/image-20230311221326848.png)









# 用户管理

## 添加用户

![image-20230311221816487](LINUX.assets/image-20230311221816487.png)



## 指定/修改密码

![image-20230311222854469](LINUX.assets/image-20230311222854469.png)



## 删除用户

![image-20230311222902572](LINUX.assets/image-20230311222902572.png)



## 切换用户

![image-20230311223245004](LINUX.assets/image-20230311223245004.png)



## 查看当前用户/登录用户

+ 显示初始登陆用户

![image-20230311223458211](LINUX.assets/image-20230311223458211.png)



## 用户组

![image-20230311224749847](LINUX.assets/image-20230311224749847.png)

![image-20230311224725931](LINUX.assets/image-20230311224725931.png)

## id usr

+ 查看当前用户所在组

## 用户和组相关文件

![image-20230311230143587](LINUX.assets/image-20230311230143587.png)



# Linux实用指令

+ ... & //让...后台运行 

## 指定运行级别

![image-20230315203710153](LINUX.assets/image-20230315203710153.png)

+ systemctl get-default
+ systemctl set-default

![image-20230315203738693](LINUX.assets/image-20230315203738693.png)



## root找回密码 



## 帮助指令

![image-20230315205223514](LINUX.assets/image-20230315205223514.png)



## 文件目录类

### pwd，ls

![image-20230315205536917](LINUX.assets/image-20230315205536917.png)



### cd

![image-20230315205902443](LINUX.assets/image-20230315205902443.png)



### mkdir

![image-20230315210940899](LINUX.assets/image-20230315210940899.png)



### rmdir

![image-20230315211414549](LINUX.assets/image-20230315211414549.png)



### touch

![image-20230315211439440](LINUX.assets/image-20230315211439440.png)



### cp

![image-20230315212145919](LINUX.assets/image-20230315212145919.png)



### rm

![image-20230315212413193](LINUX.assets/image-20230315212413193.png)



### mv

![image-20230315213158566](LINUX.assets/image-20230315213158566.png)           



### cat与more（浏览）

![image-20230315213747884](LINUX.assets/image-20230315213747884.png)

![image-20230315213806749](LINUX.assets/image-20230315213806749.png)





### less（浏览）

![image-20230315214853428](LINUX.assets/image-20230315214853428.png)



### echo，head，tail

![image-20230315215939933](LINUX.assets/image-20230315215939933.png)

![image-20230315220049916](LINUX.assets/image-20230315220049916.png)

+ **ctrl+c退出监控**



### \>,>>

![image-20230315220728589](LINUX.assets/image-20230315220728589.png)



### ln(软连接)

![image-20230315222626325](LINUX.assets/image-20230315222626325.png)



### history

![image-20230315222826295](LINUX.assets/image-20230315222826295.png)



## 时间日期类

### date

![image-20230323212132767](LINUX.assets/image-20230323212132767.png)

### cal

![image-20230323212317968](LINUX.assets/image-20230323212317968.png)



## 搜索查找类

### find

![image-20230323213140432](LINUX.assets/image-20230323213140432.png)

### locate 、which

![image-20230323213436089](LINUX.assets/image-20230323213436089.png)

### grep

![image-20230323213846296](LINUX.assets/image-20230323213846296.png)

+ grep -v
  + 反向匹配



## 压缩和解压类

### gzip gunzip

![image-20230328162620713](LINUX.assets/image-20230328162620713.png)



### zip unzip

![image-20230328163308333](LINUX.assets/image-20230328163308333.png)



### tar

![image-20230328165232447](LINUX.assets/image-20230328165232447.png)





# Linux组管理和权限管理

## Linux组基本介绍

![image-20230328171925798](LINUX.assets/image-20230328171925798.png)



## 文件/目录所有者

![image-20230328172640235](LINUX.assets/image-20230328172640235.png)

![image-20230328201432439](LINUX.assets/image-20230328201432439.png)

## 文件/目录所在组

![image-20230328173922986](LINUX.assets/image-20230328173922986.png)

![image-20230328201714927](LINUX.assets/image-20230328201714927.png)



## 其他组

![image-20230328174300172](LINUX.assets/image-20230328174300172.png)



## 权限基本介绍

![image-20230328194457408](LINUX.assets/image-20230328194457408.png)

## rwx详解

![image-20230328195014055](LINUX.assets/image-20230328195014055.png)

![image-20230328195728018](LINUX.assets/image-20230328195728018.png)





## 修改权限-chmod

### 第一种方式：+ - =变更权限

![image-20230328200308556](LINUX.assets/image-20230328200308556.png)

### 第二种方式：通过数字变更权限

![image-20230328200524274](LINUX.assets/image-20230328200524274.png)



### 练习

![image-20230328204921051](LINUX.assets/image-20230328204921051.png)





# Linux定时任务调度

## crond任务调度

### -e -l -r

+ crontab

![image-20230329121325624](LINUX.assets/image-20230329121325624.png)

### 占位参数

![image-20230329121310020](LINUX.assets/image-20230329121310020.png)



### 特殊符号说明

![image-20230329121611400](LINUX.assets/image-20230329121611400.png)

### 特殊时间执行案列

![image-20230329121758235](LINUX.assets/image-20230329121758235.png)

### crond应用案例与相关指令

![image-20230329123514406](LINUX.assets/image-20230329123514406.png)



## at定时任务

### 基本介绍

#### ps -ef 与 命令格式

![image-20230329124131561](LINUX.assets/image-20230329124131561.png)



### at命令选项

![image-20230329124243524](LINUX.assets/image-20230329124243524.png)



### at时间定义

![image-20230329124500458](LINUX.assets/image-20230329124500458.png)



### at定时任务-案列

![image-20230329125638184](LINUX.assets/image-20230329125638184.png)





# Linux磁盘分区、挂载

## Linux分区

### 原理介绍

![image-20230329144617864](LINUX.assets/image-20230329144617864.png)



### 硬盘说明

![image-20230329145025644](LINUX.assets/image-20230329145025644.png)     



### 查看所有设备挂载情况

+ lsblk
+ lsblk -f

![image-20230329145315985](LINUX.assets/image-20230329145315985.png)



## 挂载经典案列

### 步骤1

![image-20230329151326131](LINUX.assets/image-20230329151326131.png)

### 步骤2-fdisk /dev/sdb

![image-20230329151549171](LINUX.assets/image-20230329151549171.png)

### 步骤3-mkfs -t ext4 /dev/sdb1

![image-20230329151717218](LINUX.assets/image-20230329151717218.png)



### 步骤4-mount /dev/sdb1 /newdisk

![image-20230329151724895](LINUX.assets/image-20230329151724895.png)



### 步骤5- vim /etc/fstab

+ 永久挂载

![image-20230329151830181](LINUX.assets/image-20230329151830181.png)



## 磁盘情况查询

### 查询系统整体磁盘占用情况--df -h

![image-20230329153536405](LINUX.assets/image-20230329153536405.png)





### 查询指定目录的磁盘占用情况-du -[选项]

![image-20230329153411036](LINUX.assets/image-20230329153411036.png)





## 磁盘工作实用指令

![image-20230329154540599](LINUX.assets/image-20230329154540599.png)





# Linux网络配置

## Linux网络配置原理图

![image-20230329161752755](LINUX.assets/image-20230329161752755.png)



## 查看网络IP和网关

### 查看虚拟网络编辑器和修改IP地址

![image-20230329173758202](LINUX.assets/image-20230329173758202.png)

### 查看网关

![image-20230329173831126](LINUX.assets/image-20230329173831126.png)



### 在Windows和Linux查看网络配置

![image-20230329170156104](LINUX.assets/image-20230329170156104.png)



### ping测试主机之间的网络连通性

![image-20230329170239913](LINUX.assets/image-20230329170239913.png)





## Linux网络环境配置

### 第一种方法（自动获取）

![image-20230329170403946](LINUX.assets/image-20230329170403946.png)



### 第二种方法（指定ip）

![image-20230329171348271](LINUX.assets/image-20230329171348271.png)

![image-20230329171444815](LINUX.assets/image-20230329171444815.png)



## 设置主机名和hosts映射

### 设置主机名

![image-20230329172430499](LINUX.assets/image-20230329172430499.png)



### 设置hosts映射

![image-20230329172503371](LINUX.assets/image-20230329172503371.png)



### 主机名解析机制分析（Hosts、DNS）

![image-20230329173331587](LINUX.assets/image-20230329173331587.png)







# Linux进程管理

## 基本介绍

![image-20230330154205288](LINUX.assets/image-20230330154205288.png)



## 显示系统执行的进程-ps

### 基本介绍

![image-20230330154829193](LINUX.assets/image-20230330154829193.png)

### ps详解

![image-20230330155124202](LINUX.assets/image-20230330155124202.png)

### 应用实例

![image-20230330155907573](LINUX.assets/image-20230330155907573.png)



### 查看进程树-pstree

![image-20230330161813263](LINUX.assets/image-20230330161813263.png)







## 终止进程-kill killall

![image-20230330161434706](LINUX.assets/image-20230330161434706.png)





## Linux服务管理

### 介绍-service-守护进程

![image-20230330163255066](LINUX.assets/image-20230330163255066.png)

### 查看服务名

![image-20230330163322904](LINUX.assets/image-20230330163322904.png)



### 服务的运行级别

![image-20230330163524958](LINUX.assets/image-20230330163524958.png)

+ systemctl get-default
+ systemctl set-default

![image-20230330164042142](LINUX.assets/image-20230330164042142.png)





### chkconfig-服务在各个运行级别的开/关

![image-20230330164459661](LINUX.assets/image-20230330164459661.png)



### systemctl管理指令

![image-20230330170708760](LINUX.assets/image-20230330170708760.png)





### 打开或关闭指定端口-firewall

![image-20230330171658194](LINUX.assets/image-20230330171658194.png)







## 动态监控进程-top

### 介绍

![image-20230330172845829](LINUX.assets/image-20230330172845829.png)



### top交互操作说明

![image-20230330173643205](LINUX.assets/image-20230330173643205.png)





## 监控网络状态-netstat -ping

![image-20230330175340004](LINUX.assets/image-20230330175340004.png)





# Linux RPM 与 YUM

## rpm包管理

### 简单查询指令

![image-20230330191327530](LINUX.assets/image-20230330191327530.png)

### 其他查询指令

![image-20230330191825775](LINUX.assets/image-20230330191825775.png)



### ==卸载==-rpm -e RPM包名

![image-20230330192841450](LINUX.assets/image-20230330192841450.png)



### ==安装==-rpm -ivh RPM包全路径名

![image-20230330192932130](LINUX.assets/image-20230330192932130.png)



## yum

![image-20230330194014268](LINUX.assets/image-20230330194014268.png)



# shell编程

## shell是什么

![image-20230330194556985](LINUX.assets/image-20230330194556985.png)



## shell脚本的执行方式

+ shell脚本格式要求

![image-20230330195032460](LINUX.assets/image-20230330195032460.png)



## shell变量

### 介绍与定义

![image-20230410210221182](LINUX.assets/image-20230410210221182.png)

### 规则

![image-20230410210513608](LINUX.assets/image-20230410210513608.png)



### 设置环境变量

![image-20230410211546265](LINUX.assets/image-20230410211546265.png)



### 位置参数变量

![image-20230410211907092](LINUX.assets/image-20230410211907092.png)



### 预定义变量

![image-20230410212507532](LINUX.assets/image-20230410212507532.png)





## 运算符

![image-20230410213557018](LINUX.assets/image-20230410213557018.png)





## 条件判断

### 判断语句

![image-20230410214827923](LINUX.assets/image-20230410214827923.png)



### 常用判断条件

![image-20230410214909344](LINUX.assets/image-20230410214909344.png)



## 流程控制

### if判断

![image-20230410214841454](LINUX.assets/image-20230410214841454.png)



### case语句

![image-20230410215456418](LINUX.assets/image-20230410215456418.png)



### for循环

![image-20230410220211905](LINUX.assets/image-20230410220211905.png)



### while循环

![image-20230410221354001](LINUX.assets/image-20230410221354001.png)



## read获取输入

![image-20230410221640166](LINUX.assets/image-20230410221640166.png)



## 函数

### 系统函数

![image-20230410222042907](LINUX.assets/image-20230410222042907.png) 

![image-20230410222221659](LINUX.assets/image-20230410222221659.png)



### 自定义函数

![image-20230410223040188](LINUX.assets/image-20230410223040188.png)



##  shell编程综合案例

![image-20230410224350616](LINUX.assets/image-20230410224350616.png)

![image-20230410231505337](LINUX.assets/image-20230410231505337.png)





# Linux日志管理

## 日志介绍和实例

### 基本介绍

![image-20230411204648948](LINUX.assets/image-20230411204648948.png)



### 系统常用日志

![image-20230411205953350](LINUX.assets/image-20230411205953350.png)



### 应用案例

![image-20230411210400211](LINUX.assets/image-20230411210400211.png)



## 日志管理服务rsyslogd

### 日志服务原理图

![image-20230411210759638](LINUX.assets/image-20230411210759638.png)



### 配置文件及格式

![image-20230411211954910](LINUX.assets/image-20230411211954910.png)

![image-20230411212012926](LINUX.assets/image-20230411212012926.png)



### 日志文件格式

![image-20230411211857242](LINUX.assets/image-20230411211857242.png)



### 自定义日志服务

![image-20230411212445573](LINUX.assets/image-20230411212445573.png)

![image-20230411221435054](LINUX.assets/image-20230411221435054.png)





## 日志轮替

### 介绍

![image-20230411220125275](LINUX.assets/image-20230411220125275.png)

### logrotate配置文件

![image-20230411220417213](LINUX.assets/image-20230411220417213.png)

#### 参数说明

![image-20230411220637134](LINUX.assets/image-20230411220637134.png)



### 自定义日志轮替

![image-20230411220830598](LINUX.assets/image-20230411220830598.png)

<img src="LINUX.assets/image-20230411221110084.png" alt="image-20230411221110084" style="zoom: 80%;" />



### 日志轮替机制原理

![image-20230411221622266](LINUX.assets/image-20230411221622266.png)





## 查看内存日志

![image-20230411222204722](LINUX.assets/image-20230411222204722.png)





# 定制自己的Linux

## 基本介绍

![image-20230411222826360](LINUX.assets/image-20230411222826360.png)



## 基本原理

![image-20230411222925848](LINUX.assets/image-20230411222925848.png)



## 制作mini Linux的思路分析

![image-20230411223100721](LINUX.assets/image-20230411223100721.png)

<img src="LINUX.assets/image-20230411223500742.png" alt="image-20230411223500742" style="zoom:50%;" />





# Linux内核源码&内核升级

## 为什么要阅读Linux内核

![image-20230412152354497](LINUX.assets/image-20230412152354497.png)



## 基本介绍

![image-20230412152317682](LINUX.assets/image-20230412152317682.png)



## 源码阅读技巧

![image-20230412152708542](LINUX.assets/image-20230412152708542.png)



## Linux内核最新版和内核升级

### 最新版

![image-20230412154725851](LINUX.assets/image-20230412154725851.png)

### 内核升级

![image-20230412154700094](LINUX.assets/image-20230412154700094.png)



# 备份与恢复介绍

## 基本介绍

![image-20230412155440078](LINUX.assets/image-20230412155440078.png)



## 安装dump和restore

![image-20230412155619597](LINUX.assets/image-20230412155619597.png)



## 用dump完成备份

### 基本介绍

![image-20230412160222768](LINUX.assets/image-20230412160222768.png)

### 应用案例

![image-20230412160525841](LINUX.assets/image-20230412160525841.png)

### dump -W

![image-20230412160646181](LINUX.assets/image-20230412160646181.png)

### dump备份文件或目录-不支持增量备份

![image-20230412161112939](LINUX.assets/image-20230412161112939.png)



## 用restore完成恢复

### 基本介绍和基本语法

![image-20230412161546683](LINUX.assets/image-20230412161546683.png)



### 应用案例

#### 比较模式

![image-20230412161707514](LINUX.assets/image-20230412161707514.png)

#### 查看模式

![image-20230412162559818](LINUX.assets/image-20230412162559818.png)

#### 还原模式

![image-20230412162539292](LINUX.assets/image-20230412162539292.png)

![image-20230412162518745](LINUX.assets/image-20230412162518745.png)





# Linux可视化管理 webmin和bt运维工具\

## bt

### bt安装

![image-20230412170346021](LINUX.assets/image-20230412170346021.png)

![image-20230412170318243](LINUX.assets/image-20230412170318243.png)

### 查看用户密码等

![image-20230412170411998](LINUX.assets/image-20230412170411998.png)







# Linux面试题-12

p142-153



# end