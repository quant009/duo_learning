## R语言安装package相关

R语言安装package用语法: install.packages(package_name)



## data.frame

### 显示data.frame的summary信息



## tsv文件

### 基本概念

1.tsv文件用制表符（Tab键）分隔每列数据，全称:  Tab Seperated Value File。

2.csv文件用逗号分隔每列数据，全称: Comma Seperated Value File。

3.tsv文件示例：

![image-20201005200739320](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20201005200739320.png)

4.csv文件示例



### R语言读取tsv文件

R语言读取tsv文件要用到readr这个package，回顾下readr是tidyverse的package。那么tidyverse中有哪些package呢？(可以用install.packages('tidyverse')一键安装所有tidyverse包。)

**tidyverse中的包有: ggplot2, dplyr, tidyr, readr, purrr, tibble, stringr, forcats。**

要在R语言中导入tsv文件，要使用readr中的read_tsv。关于read_tsv，可以参考以下网址：

https://www.rdocumentation.org/packages/readr/versions/1.0.0/topics/read_delim









