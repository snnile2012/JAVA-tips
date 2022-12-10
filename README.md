# JAVA-tips
JAVA中有趣的知识点  
## 1.String的最大长度及最大占用空间：
String的底层实现是char类型的数组，而该数组的长度是int类型，即该数组的最大长度为Integer.MAX_VALUE:（2^31）-1 = 2147483647；  
char类型占位2Byte，因此最大占用空间为 2147483647*2Byte = 4294967294Byte = 4GB
 
## 2.并行与并发：
![image](https://github.com/snnile2012/JAVA-tips/blob/master/pics/concurrent.jpg)

## 3.代表数字的char转int：
有一个char类型的变量a='9'，如何转换为int 9？
```java
char a = '9';
int b = a - '0';
```
