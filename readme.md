# 内容提要
根据上课的知识点进度划分为不同的分支，供2204班级学员跟近下载

## 1. 课堂之前的一些准备工作

1. 安装好`Git`工具

   下载地址 [https://git-scm.com/](https://git-scm.com/)

   如果安装过程中有错误，可以先自行百度一下，最好是重新安装完整版的`win10`

2. 安装社区版（Comunity）的`IDEA`，社区版一般都是免费且合法的，以后在项目开发中，涉及到商业化的项目，不会有侵权一说。

3. 通过`IDEA`新建项目

   选择 `Get from VCS`创建

   ![image-20220711151116591](images/image-20220711151116591.png)

如果已经打开`IDEA`中的某一个项目，然后需要从某一个远程仓库中拉取一个新的项目，可以选择 `File -> New -> Project from Version Control...`

## 2. Git基本操作

### 2.1 基本指令含义

- fetch 刷新分支列表，让本地和远程仓库的分支信息保持同步
- commit 提交代码改变至本地仓库缓存
- push 提交本地仓库缓存到远程仓库
- update 更新本地仓库缓存到最新版本

### 2.2 如何理解和使用branch

`branch`是某一个时间节点上的代码的集合，代表针对某一个特定的需求所编写的代码内容集合，`branch`的命名规范每一个项目组都各有不同，进行开发前，需向项目组进行了解

### 2.3 切换分支

在`IDEA`右下角点击分支标签，展开分支浏览窗口，鼠标左键点击要切换的分支，选择`Check out`即可

> 需注意：在切换新的分支的时候，原先老分支未提交的内容需要执行`commit`，否则，改动的内容会被带到切换的新分支中去

### 2.4 其它菜单操作

- 在`Git -> Manage Remotes`中，可以管理远程仓库路径
- 选择某一个文件，点击右键，选择`Git -> Compare with Branch...`，然后选择具体的另一个分支，可以在当前分支和另一个分支之间，比较某一个文件的异同

## 3. 课外练习

```java
// 阅读 docsify 官方文档，制作自己的技术博客（1周）
// 官方文档 https://docsify.js.org/#/zh-cn/
// 视频参考 https://www.bilibili.com/video/BV1kT4y1T7wY?spm_id_from=333.337.search-card.all.click


// 编写一个工具类，能随机生成如下信息
// 1、随机生成指定长度的字符串（字符串内容选择范围为[A-Za-z]）
// 2、随机生成1-100之间的整数
// 3、随机生成性别字符串(male / female)

// 利用上述的工具类，按照要求创建以下信息集合
// 1、创建一个长度为100的学生数组
// 2、学生姓名随机生成
// 3、要求学生的性别男女比例为1:1
// 4、学生的年龄构成为[18, 20)占20%，[20-25) 占50%，其余占30%

// 按照如下要求输出所有学员信息
// 1、输出学员信息列表
// 2、输出实际生成的学生统计信息（男女比例，年龄比例）

// 将生成的学员信息集合导出至Excel
// 可参考如下官方文档：
// https://easyexcel.opensource.alibaba.com/docs/current/

// 生成一下时间有关统计信息
// 1、输出生成学生集合的耗时
// 2、输出导出为excel文件的耗时
// 将集合的长度分别定为 100 、 10_000 、100_000 进行多次实验，观察结果的变化
```

