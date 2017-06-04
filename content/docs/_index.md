+++
date = "2017-06-04T15:21:18+08:00"
icon = "<b>1. </b>"
title = "MyBatis 通用 Mapper"
weight = 0

+++

### MyBatis

# 通用 Mapper 3

[![Maven central](https://maven-badges.herokuapp.com/maven-central/tk.mybatis/mapper/badge.svg)](https://maven-badges.herokuapp.com/maven-central/tk.mybatis/mapper)

### [@liuzh](https://github.com/abel533)

通用Mapper都可以极大的方便开发人员。可以随意的按照自己的需要选择通用方法，还可以很方便的开发自己的通用方法。

极其方便的使用MyBatis单表的增删改查。

支持单表操作，不支持通用的多表联合查询。

### 支持 Mybatis-3.2.4 及以上版本

### <span style="color:red">特别强调</span>

- **不是表中字段的属性必须加 `@Transient` 注解**
- **通用 Mapper 不支持 devtools 热加载**，devtools 排除实体类包即可，配置方式参考：[using-boot-devtools-customizing-classload](http://docs.spring.io/spring-boot/docs/current/reference/html/using-boot-devtools.html#using-boot-devtools-customizing-classload)
