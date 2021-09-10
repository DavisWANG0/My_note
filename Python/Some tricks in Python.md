# 1 读取txt文件的方法

## 1.1 读取zh文件

### 1.1.1 不会出现\n

```python
# 1
f=open("filename", encoding='gbk')
txt=[]
for line in f:
	txt.append(line.strip())
print(txt)

# 2
f=open('唐诗一百首.txt')
line = f.readline().strip() #读取第一行
txt=[]
txt.append(line)
while line:  # 直到读取完文件
   line = f.readline().strip()  # 读取一行文件，包括换行符
   txt.append(line)
f.close()  # 关闭文件
print(txt)
```

### 1.1.2 每行末尾有\n

```text
f=open('唐诗一百首.txt')
data = f.readlines()  # 直接将文件中按行读到list里，效果与方法2一样
f.close()  # 关
print(data) #返回list
```

## 1.2 读取数据文件

```text
import numpy as np
data = np.genfromtxt("filename.txt",dtype=[int, float,int])  # 将文件中数据加载到data数组里
print(data)
```

# 2 list后加元素的三种方法

## 2.1 “+”

## 2.2 append()

```python
l = ['Python', 'C++', 'Java']
#追加元素
l.append('PHP')
print(l)

#追加元组，整个元组被当成一个元素
t = ('JavaScript', 'C#', 'Go')
l.append(t)
print(l)

#追加列表，整个列表也被当成一个元素
l.append(['Ruby', 'SQL'])
print(l)

```

## 2.3 extend(）

```python
l = ['Python', 'C++', 'Java']
#追加元素
l.extend('C')
print(l)

#追加元组，元祖被拆分成多个元素
t = ('JavaScript', 'C#', 'Go')
l.extend(t)
print(l)

#追加列表，列表也被拆分成多个元素
l.extend(['Ruby', 'SQL'])
print(l)

```

# 3 读txt文件的方法

file = open("xxx.txt")

