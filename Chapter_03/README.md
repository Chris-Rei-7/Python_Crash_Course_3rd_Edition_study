5.18

1. bikes = ['trek', 'redline', 'giant']
print(bikes[0])
print(bikes[2], bikes[-1])
运行结果trek
giant giant

2. 和其他变量一样，我们可以使用列表中的各个值例如，在 f-字符串中，我们可以根据列表中的值来创建消息：我们使用 bicycles[0] 的值（第一款自行车）生成了一个句子，并赋值给 message，程序的输出如下：
bicycles = ['trek', 'cannondale', 'redline', 'specialized']message = f"My first bicycle was a {bicycles[0].title()}."print(message)
运行结果My first bicycle was a Trek.

3. lst.append(val) ：在列表的末尾添加新元素。
   lst.insert(idx, val)：在列表的指定位置上添加新元素。

4. del lst[idx] ：删除列表中指定索引的元素
lst.pop([idx]) -> val：删除并返回列表中指定索引（默认为末尾） 的元素，弹出（pop）的值能被接着使用

5. lst.remove(val)：删除列表中匹配到的第一个指定元素

6. lst.sort() ：永久修改原列表，对其中的元素进行排序。sorted(lst) -> lst'：返回排序后的列表的副本。

7. lst.reverse()：永久修改原列表，对其中的元素进行翻转

8. len(lst) -> num：获取列表的元素个数。