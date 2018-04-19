# MySQL
About mysql's study.

## Character type

### 数字类型:
-------------------
1. TINYINT----存储要求：1 个字节 （-128，127），（0，255）
2. SMALLINT----存储要求：2 个字节 （932768，32767），（0，4294967295）
3. MEDIUMINT----存储要求：3 个字节  （-8388608，8388607），（0，16777215）
4. INT\INTEGER----存储要求：4 个字节 （-2147483648，214747483647），（0，4294967295）
5. BIGINT----存储要求： 8 个字节（-9223372036854775808 ，9223372036854775807），（0，18446744073709551615）
6. FLOAT----存储要求：4 个字节 （-3.402823466E+38，-1.175494351E-38）
7. DOUBLE----存储要求：8 个字节 （-1.7976931348623157E+308，-2.2250738585072014E-307）
8. DOUBLE PRECSION
9. REAL
10. DECIMAL----存储要求：M字节（低于3.23 版本）M+2 字节（3.23 或更高版本） 
11. NUMERIC

### 字符串列类型:
-------------------
1. CHAR
2. VARCHAR
3. TINYBLOB
4. TINYTEXT
5. BLOB
6. TEXT
7. MEDIUMBLOB
8. LONGBLOB
9. LONGTEXT
10. ENUM
11. SET

### 时间类型:
-------------------
1. DATE---YYYY-MM-DD 取值范围：“1000-01-01”到“9999-12-31” 存储需求：3 字节 
2. TIME----YYYY-MM-DD 取值范围：“-838:59:59”到“838:59:59” 存储需求：3 字节 
3. DATETIME----max(255) 取值范围：“1000-01-01 00:00:00”到“9999-12-31 23:59:59” 存储需求：8 字节 
4. TIMESTAMP----YYYYMMDDHHMMSS 取值范围：“19700101000000”到 2037 年的某个时刻 存储需求：4 字节 
5. YEAR----取值范围：1901 到 2155 存储需求：1 字节 

## grammar

### 创建模式，数据库，表格，视图，索引
--------------------
* CREATE DATABASE YOURDATABASE'S NAME;
* CREATE TABLE YOURTABLE'S NAME(attribute1 type，attribute2 type,...);
> type中，一般是对元组属性的描述，常用的有not null,auto_increment,primary key等等
* CREATE VIEW YOURVIEW'S NAME;
* CREATE INDEX XXX;

### 一些基本操作
--------------------
+ select * from where group by order by;
+ insert into xxx values();
+ alter table xxx rename/add/drop/alter
+ insert into ....
