# JAVA

## Class 1

### 1 分数组成

考勤10% 编程考试20% 团队作业A（20%），团队作业B（50%）

### 2 变量

> 4种类型
>
> - instance variables(non-static fields)
> - class variables(static fields)
> - local variables
> - parameters

Java is statically-typed, which means variables must be declared first before using.

> 8 primitive data types
>
> - byte, short, int, long
>
> - float, double
>
> - boolean
>
> - char(2 bytes)
>
>   Also, these is a special support for character strings. But the string is immutable.

#### literal

​	long s=5l;

​	float s=3.1f;

​	double s=3.14e10;

！java break

#### Array

​	a container object

```java
int[] anArray;
anArray = new int[10];
length of array：arrayRefVar.lenth
int[] anArray = {100,200,300,400,500};
```

**Enhancement:**

```java
int[] elements = {1,2,3,4,5}
for (int a: elements){
	System.out.println(a);
}
```

**java is passing by value**

## Class 2

RECOMENDATION of  some books:

1. Thinking in JAVA
2. Efective Java

### Numbers and Strings

衡量算法时间：long t = System.nanoTime();

StingBuilder Class更快

### Classes and Objects

```python
public static int add(int... num){
	int res = 0;
    for(int a:num){
        res += a;
	}
    return res;
}
```

singleton 单身人士

# Class 3



## Interface

1.接口 2.界面

> A reference type, that can contain only constants, method signatures, default methods, static methods, and nested types
>
> 引用类型，只能包含常量、方法签名、默认方法、静态方法和嵌套类型 

Interfaces cannot be instantiated、

接口不能被实例化

## Multiple Inheritance

多重继承

