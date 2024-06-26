---
title: mysql
tags: 
- mysql
date: 2024-3-11
author: cheng
--- 

# MySQL 

## 简介
SQL是Structured Query Language（结构化查询语言）的缩写。它是一种专门用于访问和处理数据库（database，缩写DB）的语言。数据库是一个很宽泛的概念。这里我们讨论的是 - SQL数据库，通常也称关系数据库（Relational Database[1]，缩写RDB）。而关系数据库是由表（Table）组成的。


## 表名、列、行 和 主键
表名是数据库中表的唯一标记，列是表中数据的字段，行是表中数据的记录。主键是表中唯一且不重复的列，主键是表的唯一标识符，主键必须是唯一的，不可重复的。

主键的特点：
1. 任意两行都不具有相同的值
2. 不存在NULL值
3. 主键列中的值不允许修改或更新
4. 即使行被删除，它的主键值也不会赋予其他的新行


## 编码规范
1. 关键字大写，表名、列名小写，单词间使用下划线连接。
2. 表名、列名使用集合名称，避免使用复数形式。如 staff(推荐) 和 employees