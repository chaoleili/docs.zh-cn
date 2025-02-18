# years_diff

## 功能

计算 `expr1` - `expr2`，结果精确到年。

## 语法

```Haskell
years_diff(expr1,expr2);
```

## 参数说明

`expr1`: 支持的数据类型为 DATETIME。

`expr2`: 支持的数据类型为 DATETIME。

## 返回值说明

返回值的数据类型为 BIGINT。

## 示例

```Plain Text
mysql> select years_diff('2010-11-30 23:59:59', '2000-11-1 23:59:59');
+---------------------------------------------------------+
| years_diff('2010-11-30 23:59:59', '2000-11-1 23:59:59') |
+---------------------------------------------------------+
|                                                      10 |
+---------------------------------------------------------+
1 row in set (0.00 sec)
```
