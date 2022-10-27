## Ubutu系统使用


### CLI(Command Line Interface)

```
#当前目录下文件个数
ll | wc -l

#统计当前文件夹下文件的个数，包括子文件夹里的
ls -lR|grep "^-"|wc -l
```