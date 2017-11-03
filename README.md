# 史上最简单的 MySQL 教程


　　数据库（Database）是按照数据结构来组织、存储和管理数据的仓库，它产生于距今六十多年前，随着信息技术和市场的发展，特别是二十世纪九十年代以后，数据管理不再仅仅是存储和管理数据，而转变成用户所需要的各种数据管理的方式。数据库有很多种类型，从最简单的存储有各种数据的表格到能够进行海量数据存储的大型数据库系统都在各个方面得到了广泛的应用。在这里，作者将详细讲述 MySQL 数据库的相关知识，以供大家参考。当然，也需要在此声明：**如果文章中出现了错误，请大家帮忙斧正，深感荣幸。**

## 目录

第 1 篇：[史上最简单的 MySQL 教程（一）「数据库」](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/database.md)

第 2 篇：[史上最简单的 MySQL 教程（二）「关系型数据库」](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/relation-db.md)

第 3 篇：[史上最简单的 MySQL 教程（三）「 MySQL 数据库」](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/mysql_db.md)

第 4 篇：[史上最简单的 MySQL 教程（四）「SQL 基本操作」](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/sql-operation.md)

第 5 篇：[史上最简单的 MySQL 教程（五）「中文数据问题」](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/chinese-data.md)

第 6 篇：[史上最简单的 MySQL 教程（六）「校对集问题」](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/collate.md)

第 7 篇：[史上最简单的 MySQL 教程（七）「列类型」](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/column-type.md)

第 8 篇：[史上最简单的 MySQL 教程（八）「记录长度」](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/record-length.md)

第 9 篇：[史上最简单的 MySQL 教程（九）「列属性 之 空属性、列描述和默认值」](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/column-null-comment-default.md)

第 10 篇：[史上最简单的 MySQL 教程（十）「列属性 之 主键」](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/primarykey.md)

第 11 篇：[史上最简单的 MySQL 教程（十一）「列属性 之 自动增长」](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/increment.md)

第 12 篇：[史上最简单的 MySQL 教程（十二）「列属性 之 唯一键」](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/uniquekey.md)

第 13 篇：[史上最简单的 MySQL 教程（十三）「索引」](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/index.md)

第 14 篇：[史上最简单的 MySQL 教程（十四）「关系」](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/relation.md)

第 15 篇：[史上最简单的 MySQL 教程（十五）「范式」](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/paradigm.md)

第 16 篇：[史上最简单的 MySQL 教程（十六）「数据的高级操作 之 主键冲突」](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/duplicate-primary-key.md)

第 17 篇：[史上最简单的 MySQL 教程（十七）「数据的高级操作 之 蠕虫复制」](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/worm-copy.md)

第 18 篇：[史上最简单的 MySQL 教程（十八）「数据的高级操作 之 更新 & 删除」](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/updata-and-delete.md)

第 19 篇：[史上最简单的 MySQL 教程（十九）「数据的高级操作 之 查询」](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/select.md)

第 20 篇：[史上最简单的 MySQL 教程（二十）「连接查询」](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/join-query.md)

第 21 篇：[史上最简单的 MySQL 教程（二十一）「外键」](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/foreign-key.md)

第 22 篇：[史上最简单的 MySQL 教程（二十二）「联合查询」](https://github.com/guobinhit/mysql-tutorial/blob/master/mysql-articles/union.md)

第 23 篇：[史上最简单的 MySQL 教程（二十三）「子查询」](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/sub_query.md)

第 24 篇：[史上最简单的 MySQL 教程（二十四）「视图（上）」](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/view-one.md)

第 25 篇：[史上最简单的 MySQL 教程（二十五）「视图（下）」](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/view-two.md)

第 26 篇：[史上最简单的 MySQL 教程（二十六）「数据备份与还原」](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/backup.md)

第 27 篇：[史上最简单的 MySQL 教程（二十七）「事务（上）」](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/thing-one.md)


## 教程相关

第 1 篇：[详述 MySQL 数据库的安装及配置](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/install-mysql.md)

第 2 篇：[详述 MySQL 数据库输入密码后闪退的问题及解决方案](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/resovle-method.md)

第 3 篇：[详述查看 MySQL 数据文件存储位置的方法](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/datafile.md)

第 4 篇：[详述 MySQL 导出数据遇到 secure-file-priv 的问题](https://github.com/guobinhit/mysql-tutorial/blob/master/articles/secure.md)


----------
此外，附上一句格言，望共勉：**好学若饥，谦卑若愚。**
