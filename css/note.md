优先级
===
- 最后的定义优先
p {color:red}
p {color:green}
**结论:green 优先**

- 采用计算权重的方式
每个html元素为1
每个Class元素为10
每个ID元素为100
值最大的优先
例如:
``` 
div p (2)
.class p (11)
# id p (101)
```
**结论:id p优先**

