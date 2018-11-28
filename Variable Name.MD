# 你叫啥名 

1. 起名字的目的：完全地准确地描述所代表的事物
2. 不能瞎起名字
3. 表达 “what” 而不是 “how”
4. 适当的长度
5. 使用了非常短的命名长度，潜在的意思是 这是一个不会被使用超过几行的临时变量。（比如表示循环中的下表）
6. 计算值限定词要放在名字的最后
  - Total,Sum, Average , Max, Mix, Record , String, Pointer 如果使用了这些词，要放在名字的最后

7. 变量两种最重要的部分要放在词的最前面
8. 约定俗成的对仗
    - begin/end
    - first/last
    - locked/unlocked
    - min/max
    - next/previous
    - old/new
    - opened/closed
    - visible/invisible 
    - source/target 源头和目标
    - source/destination
    - up/down
9. 为状态量起一个比 flag/status 更好的名字   
例如：dataReady, recalNeeded
10. 关于布尔变量

- done 表示事情干完，可用于标示循环结束。完成前是 false 完成后是 true
- error 表示有错误发生。正常无错为false ，有错异常为 true 
- found 表示某个值某个结果已经找到了
- success/ok 表示操作成功与否。 
- 应当有所修饰的使用以上词汇（idFound/taskSuccess/fileOK）

- status(什么状态？)/sourceFile（布尔怎么用名词？） 是非常糟糕的布尔值变量
- 布尔值的命名应该使用肯定性的词语，
- 否定性的词语在求反的时候会难以阅读（notFound/notNotFound ....）
- 使用 is  开头的 布尔变量 第二个词应该是形容词 

11. 为枚举类命名
 这段要想想再写
12. 为常量命名
- 团队要约定统一规则（多人 长期 ....从扑街吧 ）





-------------------
 表驱动编程
 1. 最有用的一点  构造查询键值来代替繁琐的条件判断