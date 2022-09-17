
## 手写函数

### 1. [大数相加](./大数相加.js) 

分析：

1. 如何实现两个非常大的数字（已经超出Number范围）的加法运算
2. 由于已经超出Number范围，因此不能用Number存，这里使用字符串存储
3. 只需要将两个数字前面补0至相同的长度，从低位到高位相加，同时用一个变量记录进位信息即可

知识点：

1. 字符串转数字：字符串前面加'+'；
2. Array.join(separator)：通过参数分隔符将数组元素连接成一个字符串；

### 2. [手写bind](./手写bind.js)