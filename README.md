#Tips


## git commit基本流程

- git status   查看更改
- git add ./   添加当前目录下的所有文件
>  如果有不需要同步到git上的文件，则新建一个“.gitignore”文件，在里面写入这些文件名（通过换行隔开）
- git commit -m "内容描述" 提交更改
- git push origin master  同步到github上 


## markdown语句基本用法

# 一级标题
## 二级标题
##### 五级标题
- 列表第一项
- 列表第二项
1. 有序列表第一项
2. 有序列表第二项
[标题](链接地址)
![图片描述](图片链接地址)
*斜体*
**粗体**
> 引用段落
```
代码块
```

| 访问 | private | default | protected | public |
| ------ | ------ | ------ | ------ | ------ | 
| 内部类 | Y | Y | Y | Y |
| 同包内 | N | Y | Y | Y |
| 同包内子类 | N | Y | Y | Y |
| 不同包下 | N | N | N | N |
| 不同包下子类 | N | N | Y | Y |
