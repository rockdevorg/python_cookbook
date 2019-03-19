### 数据结构与算法

​	python内置：`list`,` set`,`dict`，都比较简单。但是碰到`查询`，`排序`，`过滤`等问题时，我们还可以选择`collection	`这个模块

1.1 解压多个序列给多个变量

```python
a,b = [1,2] # 比较简单
```

1.2 如果一个可迭代对象元素个数不确定，可使用*运算符进行解压，

```python
first,*middle,last = list(range(20))
record = ('Dave', 'dave@example.com', '773-555-1212', '847-555-1212')
name,mail,*phone_number = record
phone_number结果为['773-555-1212', '847-555-1212']，列表类型，不管解压的结果是0个还是多个。
* 运算符能用于前中后
```

