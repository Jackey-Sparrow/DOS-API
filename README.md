# DOS-API


### 1 cd -- 改变当前目录
---

```
usage: cd [盘符:][路径][子目录名]

1. cd d:\\dos-api
2. cd.. 返回上一级
3. cd/  返回根目录

```


### 2 md -- 建立子目录
---

```
usage: md [盘符:][路径名]<子目录名>

1. md d:\dos-api\test 创建目录test
2. md d:\dos-api\test1\test 创建目录test1,并且在下面创建目录test

```

### 3 rd -- 删除子目录
---

```
usage: rm [盘符:][路径名][子目录名]
注意点：目录必须为空的才能删除，所以删除不是空的目录时候，需调用del命令删除下面所有的文件

1. del d:\dos-api\test1\*.* 删除test1目录下所有文件，不包括文件夹
2. rm d:\dos-api\test1 删除test1目录

```

