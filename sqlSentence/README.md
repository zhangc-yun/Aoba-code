### sql语句

#### 查询
  SELECT 列名称 FROM 表名称  
  SELECT id,name FROM student

#### 去重筛选
  SELECT DISTINCT 列名称 FROM 表名称
  SELECT DISTINCT id,name FROM 表名称

#### 利用操作符进行筛选
  SELECT * FROM WHERE 列名='具体的值' 
  SELECT * FROM WHERE city='beijing'  
**注意**  
如果具体的值是 文本值 加单引号  
如果具体的值是 数值 不加引号  

|操作符|描述|
| :-------- |:--: |
|=|等于|
|<>|不等于|
|>|大于|
|<|小于|
|>=|大于等于|
|<=|小于等于|
|BETWEEN|在某个范围|
|LIKE|搜索某种模式|

