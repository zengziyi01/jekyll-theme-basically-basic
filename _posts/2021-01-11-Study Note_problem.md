---
title: 注意！bug无处不在
excerpt_separator: "<!--more-->"
categories:
     - 学习笔记
---

#### 在制作jekyll过程中我遇到了非常多的问题，其中编程软件的一个小bug使我不断寻找问题。。。
<!--more-->

#### 1.我经过询问找到以下通用方法，但是很可惜并无奏效

```
1、新建一个visualc++的“win32项目”，建立一个空项目。
2、建立完成后，右键点击右边的“解决方案”中的“源文件”。
3、选择“添加”，然后添加“新建项”。
4、选择“visualc++”中的c++文件，点“添加”。
5、在新加的c++文件里面写好代码，然后保存。
6、编译运行即可。
```

#### 2.我上网查询资料，希望找到原因

- vs2015出现问题，无法修改代码，不在调试中。
- Visual Studio 2013 修改代码后无效
- 。。。。。。

#### 3.最后，在时间有限的情况下，我希望通过另一种思路解决这个问题

1. **我先发现了一些问题，我在本地保存时会出现格式变化**
2. **于是，我直接在GitHub上进行了修改**
3. **然后我将其pull到了自己的本地仓库上**
4. **最后再将其push一遍**
5. **同步仓库**
6. **清理浏览器缓存**
7. **部署成功，衬线体成功显示**

![衬线体](/zengziyi/assets/images/衬线体.png)