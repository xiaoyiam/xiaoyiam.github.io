---
layout: post
title: Mac 使用过程中遇到的问题  
date: 2022-06-07 
tags: Mac
---
    

##  1. 桌面图标突然不显示了<sup>1</sup>

如果Finder的“桌面”文件夹能看到原有的桌面文件，可能是桌面图标被隐藏了。

这种情况下，在Terminal.app执行如下命令：

```
defaults write com.apple.finder CreateDesktop true;killall Finder
```  









##  Ref  

1.  [MacBook Pro桌面文件不显示
](https://discussionschinese.apple.com/thread/251144644?answerId=252257906322#252257906322)  


##  ChangeLog 

- 2022-06-07 添加Mac桌面文件不显示  
- 