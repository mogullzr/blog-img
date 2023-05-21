# 						Java学习的第二天

## 一、java的跨平台的原理

![image-20230424095538007](C:\Users\刘遵儒\AppData\Roaming\Typora\typora-user-images\image-20230424095538007.png)

## 二、JVM，JDK,JRE

![image-20230424095859036](C:\Users\刘遵儒\AppData\Roaming\Typora\typora-user-images\image-20230424095859036.png)

## 二、制表符

![image-20230424104857243](C:\Users\刘遵儒\AppData\Roaming\Typora\typora-user-images\image-20230424104857243.png)

## 三、数据类型（增）

### 1、boolean；

### 2、byte（-128~127）；

## 四、命名规则

### 1、硬式要求

![image-20230424131330228](C:\Users\刘遵儒\AppData\Roaming\Typora\typora-user-images\image-20230424131330228.png)

### 2、软式要求

![image-20230424131605477](C:\Users\刘遵儒\AppData\Roaming\Typora\typora-user-images\image-20230424131605477.png)

## 五、键盘录入

![image-20230424131832823](C:\Users\刘遵儒\AppData\Roaming\Typora\typora-user-images\image-20230424131832823.png)

### 例如：求两个数的和代码：

```java
import java.util.Scanner
public class ScannerText{
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int i = sc.nextInt();
        System.out.println("请输入第一个数字：");
        System.out.println(i);
        int j = sc.nextInt();
        System.out.println("请输入第二个数字：");
        System.out.println(i + j);
    }
}
```

## 六、IDEA的简单介绍

### 1、方面一：

![image-20230424133546025](C:\Users\刘遵儒\AppData\Roaming\Typora\typora-user-images\image-20230424133546025.png)

![image-20230424133653405](C:\Users\刘遵儒\AppData\Roaming\Typora\typora-user-images\image-20230424133653405.png)

### 2、方面二：

### sout可快速打出System out println();

### psvm可直接打出：public static void main()

### 3、自动导入包

![image-20230424140706632](C:\Users\刘遵儒\AppData\Roaming\Typora\typora-user-images\image-20230424140706632.png)

### 4、设置忽略大小写

![image-20230424140915156](C:\Users\刘遵儒\AppData\Roaming\Typora\typora-user-images\image-20230424140915156.png)

#### 这样就可以在忽略大小写的情况下出现提示

### 5、对类的相关操作

![image-20230424141654708](C:\Users\刘遵儒\AppData\Roaming\Typora\typora-user-images\image-20230424141654708.png)

#### 改名的快捷键：shift + F6

##### 其他还有一些操作后续再讲

## 七、运算符新知识

### 1、在Java中出现了小数的计算的话，最终的结果可能会不正确：

![image-20230424142600795](C:\Users\刘遵儒\AppData\Roaming\Typora\typora-user-images\image-20230424142600795.png)

### 也有办法得到对的结果但是后面学。

### 2、在Java中整数计算只可以得到整数。

### 3、“+”的三种情况：

![image-20230424143338796](C:\Users\刘遵儒\AppData\Roaming\Typora\typora-user-images\image-20230424143338796.png)

### 4、![image-20230424143521444](C:\Users\刘遵儒\AppData\Roaming\Typora\typora-user-images\image-20230424143521444.png)![image-20230424143640031](C:\Users\刘遵儒\AppData\Roaming\Typora\typora-user-images\image-20230424143640031.png)

### （1）隐式类型转换

![image-20230424143757238](C:\Users\刘遵儒\AppData\Roaming\Typora\typora-user-images\image-20230424143757238.png)

