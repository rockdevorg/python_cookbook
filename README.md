### 数据结构与算法

​	python内置：`list`,` set`,`dict`，都比较简单。但是碰到`查询`，`排序`，`过滤`等问题时，我们还可以选择`collection	`这个模块

1.1 解压多个序列给多个变量

```python
a,b = [1,2] # 比较简单
```

1.2 如果一个可迭代对象元素个数不确定，可使用*运算符进行解压，

```python
first,*middle,last = list(range(20))
```

