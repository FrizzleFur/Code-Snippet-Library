# Code-Snippet-Library

My Code Snippet Library For Xcode

## 设置备份

Xcode 的 Code Snippet Library 路径为:


```
~/Library/Developer/Xcode/UserData/CodeSnippets/
```


`Cmd + Shift + G` 可以直接访问这个目录

Github上新建仓库名为Code Snippet Library 然后克隆到上面的目录就可以, 如果被提示目录非空, 不能Clone into, 就先到这个目录

将其中所有的.codesnippet文件拷贝到其他目录

然后终端执行

```objc
rm -rf ~/Library/Developer/Xcode/UserData/CodeSnippets/*
```

待Clone完毕后, 再将.codesnippet拷贝回来Commit, Push到远端就可以了, 以后新增或者删除了, 只需要更新远端即可, 配置新电脑的时候也可以直接Clone, 不需要从其他电脑拷贝了

## Code-Snippet列表

### Init

- property
    - `pc` -  定义一个 copy 的 property
    - `ps` - 定义一个 strong 的property
    - `blp` - 定义一个 Block 的property
- setter
    - `st` - 定义`setter`方法

```objc
if (_<#var#> != <#var#>) {
    _<#var#> = <#var#>;
    [self <#update#>];
}
```
- getter
    - `gt` - 定义`getter`方法

```objc
if (_<#var#> != <#var#>) {
    _<#var#> = <#var#>;
    [self <#update#>];
}
```

### UIKit

- button
    - `btn` - 定义一个 UIButton
    - `ada` - 定义一个 Action
- label
    - `lb` - 定义一个 UILabel
- imageview
    - `m` - 定义一个 UIImageview
- tableView
    - `tbv` - 定义一个 `UITableView`
    - `tbd` - 定义 `UITableView`的代理和Source
- collectionView
    - `cl` - 定义一个 `UICollectionView`

### View life cycle

- prama mark
    - `/` - 定义一段注释 `/** <#remark#> */`
    - `prvc` - 定义VC分割注释

## Todo 

- [ ] 添加Swift Code Snippet.

- [x] 命名各个Code-Snippet，添加前缀
- [x] 修改合适的Code-Snippet，代码
- [x] 查漏补缺
- [x] 文档上列出，将其分类
- [x] 完善Readme,补充教程

## 资源

[QMUI/QMUI_iOS_CodeSnippets: 用于Xcode使用的iOS通用代码片段，其中也包含若干专用于QMUI iOS框架的代码片段。](https://github.com/QMUI/QMUI_iOS_CodeSnippets)

## 参考

### 代码段

1. [个人积累的一些代码块(Code Snippet) –](http://ibloodline.com/articles/2016/03/27/code-snippet.html)
2. [lettleprince/XcodeSnippets: MyCodeSnippet](https://github.com/lettleprince/XcodeSnippets)
3. [QMUI/QMUI_iOS_CodeSnippets: 用于Xcode使用的iOS通用代码片段，其中也包含若干专用于QMUI iOS框架的代码片段。](https://github.com/QMUI/QMUI_iOS_CodeSnippets)
4. [使用 Git 来管理 Xcode 中的代码片段 | 唐巧的博客](http://blog.devtang.com/2012/02/04/use-git-to-manage-code-snippets/)

### 备份方法

1. [Xcode 的 Code Snippet Library 备份 – dominic's space](https://www.dominic-lian.space/2014-10/post-130)
