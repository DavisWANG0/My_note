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



​	