# 一 知识点



# 二 一些问题

### 1 `.read_csv()`，`read_excel()`哪个性能好？哪个更快？哪个更省时间？

griffinc说道：“CSV文件和TXT文件是等同的，无论是读取还是写入。另一个相同点是读写速度比EXCEL快，快得多。当然xlsx格式的文件小。”

### 2 **xlrd.biffh.XLRDError: Excel xlsx file; not supported**

在运用python中xlrd库读取.xlsx文件时报错，无法读取。这是由于当前python中的xlrd版本过高导致的，高版本下删除的对应的.xlsx读取方法。因此选择xlrd==1.2.0。

