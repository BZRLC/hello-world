# Git初级教程

有时间的可以先看看教程：

1. http://rogerdudler.github.io/git-guide/index.zh.html

2. http://kbroman.org/github_tutorial/

3. [官方教程Git-pro-V2.0](https://git-scm.com/book/zh/v2)

## 下载github repository

Github 提供两种下载方式：一种是ssh key；另外一种是https。

初学者可以直接使用https，前提是没有开通两步验证。
但是我觉得使用ssh key 比较好一点，相对来说要安全一点。下面重点来讲解ssh key。

**命令**：`$ git clone ...`

## 配置ssh key

详情见我的博客
http://brucezhaor.github.io/blog/2016/02/10/git-intro/

## 三板斧

```bash
$ git add .
$ git commit -m ""
$ git push
```
有了以上三板斧足矣胜任大多数的github操作，但是完全不能发挥git的强大功能。

## 了解git的三种状态

unstage，stage，commit

参考链接:

http://www.cnblogs.com/fengyv/archive/2014/06/16/3791588.html

## 撤销

当你修改了某些文件，然后通过测试发现效果并不好，你想要回到原来的状态怎么办？

```bash
$ git status
$ git checkout .
```

## 时光机

[版本回退](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/0013744142037508cf42e51debf49668810645e02887691000)

## 分支的玩法

参考小赵的博客：http://brucezhaor.github.io/blog/2016/02/25/git-junior/#section-4

http://www.ruanyifeng.com/blog/2012/07/git.html

http://www.ruanyifeng.com/blog/2015/12/git-workflow.html

## Pull request

简称 PR，为别人的开源项目贡献代码。。

## 常用命令参考

http://www.ruanyifeng.com/blog/2015/12/git-cheat-sheet.html?utm_source=tool.lu