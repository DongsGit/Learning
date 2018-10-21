## 						Oracle

### 1.cmd修改用户密码：

~~~
(1).登陆sqlplus/nolog;sqlplus system/manager;./sqlplus;
(2).连接数据库：connect /as sysdba;
(3).修改用户密码(例：修改sys用户密码为123）：alter user sys identified by 123;
~~~

### 2.命令导出与导入：

~~~~
(1).命令导出：exp user_xx/123@192.168.1.xx:1521/orcl  file=e:\foa.dmp  owner=(foa) 
(2).命令导入：imp user_xx/123@192.168.1.xx:1521/orcl file="e:\foa.dmp" full=y buffer=64000；
~~~~

### 3.用户授权：

~~~
(1).授权某个用户的dba权限：grant dba to 用户名;
(2).取消dba授权:revoke dba from 用户名;
~~~



