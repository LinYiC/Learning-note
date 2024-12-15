# markdown Learning-note
[TOC]
<a href="#三级标题">跳转</a>

# 一级标题
## 二级标题，类推
### 三级标题
一级标题
=====
二级标题
--------
一个新段落 


**加粗**
*斜体*
> 一个块引用
>>二级块引用
> - 块引用的组合
 
1. 有序列表测试
2. 有序列表测试
4. 有序列表测试
 
- 无序列表测试
* 无序列表测试
+ 无序列表测试

代码块测试
    
    hello，world
    
部分代码hello,`world` 

[markdown表格工具](https://www.tablesgenerator.com/markdown_tables)
[转化电子书](https://leanpub.com/)
[速查表](https://markdown.com.cn/cheat-sheet.html#%E6%80%BB%E8%A7%88)

分割线
***
---
___
[语法教程](https://markdown.com.cn/basic-syntax/links.html)
![雀](https://note.youdao.com/yws/res/78114/E7647F5DF1B24D0D893B604C182CDB38)
[![雀](https://note.youdao.com/yws/res/78114/E7647F5DF1B24D0D893B604C182CDB38)](https://markdown.com.cn/)
```
{hello,world}
```

术语
: 定义

~~delete~~likethis

- [x] 1
- [ ] 2
- [ ] 3


```math
E = mc^2
```
LR RL TB BT
```
graph LR
    A-->B
    C[1]---D(2)
    E -->|123|F

```
```
graph TD
    A[first] -->B(second)
    B -->C{third}
    C -->|one| D((fourth))
    C -->|two| F[fifth]
```
```
gantt
dateFormat YYYY-MM-DD
section S1
T1: 2014-01-01, 9d
section S2
T2: 2014-01-11, 9d
section S3
T3: 2014-01-02, 9d
```
```
sequenceDiagram
    loop 1
        lin ->>yu:hello
        yu -->>lin:ok
    end
```
