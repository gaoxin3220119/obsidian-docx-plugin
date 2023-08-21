# obsidian-docx-plugin


可以下载玩玩，源码就不放了

需要将 **docxjs.zip** 解压后保存到 .obsidian 目录下。注意不是放在 .obsidian\plugins 目录下面【新版本可以设置目录，但建议别动】。

之前用过一个插件，作者没有写清楚，折腾半天：（

在 *Yaml* 区加入下面代码：

```
---
gx-docx: docx的绝对地址 【现在可以支持在 obsidian 根目录下的相对地址引用，如：./XXX.docx 】

gx-data: []
---
```

只支持高亮，复制高亮到笔记，如果需要编辑，可以选择在菜单栏选择 “用默认Docx应用打开”来编辑

感谢 [DLillard0](https://github.com/DLillard0) 大神！！！高亮代码直接用的他的。
另外还用了[VolodymyrBaydalka](https://github.com/VolodymyrBaydalka/docxjs)的docxjs。
