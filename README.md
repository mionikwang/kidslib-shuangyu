
# Goal

Generate html for individual book.  Book contents are in db/*.csv

我们先生成每本书单独的csv文件。

# Usage
## 参数写死在脚本中

为了方便使用rake。

## rake

用rake并查看帮助。

rake -T 列出所有任务

## 一期
01...rb和02..rb

都可以不带任何参数运行。参数都写死在脚本了。

## 二期

mergeexcel.py使用方法

    python3 03-merge-excel.py db/2-qi-xls -f*xls

输出的文件在脚本执行的目录。输出的文件是tsv。

然后运行03..05的rb脚本。不需要带参数。

# Note

A customized bookify plugin for turning page is used.

<https://github.com/404pnf/bookify>
