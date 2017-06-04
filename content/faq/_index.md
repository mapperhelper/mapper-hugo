+++
date = "2017-06-04T15:21:18+08:00"
icon = "<b>3. </b>"
title = "Mapper 常见问题和用法"
weight = 90

+++

## 1. 查询时如何进行排序?

Mapper3在查询的时候支持通过 `@OrderBy` 注解来设置默认的排序方式。

当需要特殊排序时，可以使用Example(或Condition)查询，通过`setOrderByClause`方法设置排序的列。
