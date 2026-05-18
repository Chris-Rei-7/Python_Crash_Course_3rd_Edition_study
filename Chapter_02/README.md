5.18

1. 变量只能包含字母、数字和下划线，不能以数字开头

2. 字符串（string）就是一系列字符•在 Python 中，用英文引号引起的都是字符串•引号可以是双引号，也可以是单引号•还有一种特殊的写法，使用三个单引号或三个双引号•三个引号可以创建跨行字符串
"""Hello Python world!
Hello iTuring!"""

3. 一个引号的写法也可以跨行，只需要在每行的末尾加入表示连接的字符（\）即可，但这种写法并不会保留换行，而三个引号的写法将会保留括起的所有内容，两者均会包括开头和末尾添加的额外空白：

>>>"Hello Python world! \

Hello iTuring!"

Hello Python world! Hello iTuring!

>>>"""Hello Python world!

Hello iTuring!"""

Hello Python world!

Hello iTuring!

4. 方法是特殊的函数

5. upper()：将字符串全部改为大写
   lower()：将字符串全部改为小写
   title()：每个单词的首字母大写

6. \t：在字符串中表示制表符。
   \n：在字符串中表示换行符。

7. 我们可以在 f-字符串中，使用花括号来引用代码中定义的变量f 是 format 的简写
first_name = "ada"last_name = "lovelace"full_name = f"{first_name} {last_name}"print(full_name)message = f"Hello, {full_name.title()}!"print(message)

8. lstrip()：移除左端的空白
   rstrip()：移除右端的空白
   strip() ：移除两端的空白

9. removeprefix()：移除字符串中指定的前缀
url = 'https://www.ituring.com.cn'url = url.removeprefix('https://')print(url)

10. "Hello" + " iTuring"
"Hello iTuring"
"Hello " * 2
"Hello Hello "

11. 整数（integer）：不带小数点的数
    浮点数（float）：带小数点的数可在数中添加下划线使大数更易读
    1_000_0001_000_000.5

12. 双斜杠（//）：表示整数除法
    双乘号（**）：表示乘方运算
    print(3 // 3)
    print(2.5 // 2)
    print(1 // 2)
    print(1.5 // 1.5)
    运行结果
    1
    1.0
    0
    1.0

13. Python 支持在一行代码中给多个变量赋值： 
    x, y, z = 0, 0, 0

14.  没有内置的常量支持，我们给出的是一个约定俗成的惯例使用全大写字母（单词由下划线分割）来将某个变量视为常量

15. Python 中使用（#）标识注释