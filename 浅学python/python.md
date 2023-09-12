# python

## 第一天

### 1、解释型语言

### 2、小游戏（猜随机数）

```python
import random
num = random.randint(1,100) # 获得一个随机数
is_done = Fasle #是否猜中的标记
count = 0 # 玩家猜了几次
while not is_done:
    guess = int(intput('请输入一个【1，100】的整数：'))
    if guess == num:
        is_done = Ture
    elif guess < num:
        print('小了，再猜猜！')
    elif guess > num:
        print('大了，再猜猜！')
        count += 1
print('恭喜你，猜了{}次，终于猜对了！答案是{}！'.format(count,num))
```

### 3、数据运算

*乘 ，+加，-减，/除

//取整（向下）%取余

**幂运算

### 4、字符串

len()#计算字符串的长度

ord()#转换为编码

chr()#转换为字符

format( )格式化字符串：

![image-20230222214217841](C:\Users\volet\AppData\Roaming\Typora\typora-user-images\image-20230222214217841.png)



