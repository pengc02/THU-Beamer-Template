# THU-Beamer-Template

最初能追溯到的版本是：

 [https://www.latexstudio.net/archives/4051.html](https://www.latexstudio.net/archives/4051.html)



同时还见过另外的版本：

https://github.com/tl3shi/THUBeamer.git

https://github.com/YangLaTeX/thubeamer.git



前代版本：

Jiayi Weng 学长进行了多次修改

Overleaf模板位于：[https://www.overleaf.com/latex/templates/thu-beamer-theme/vwnqmzndvwyb](https://www.overleaf.com/latex/templates/thu-beamer-theme/vwnqmzndvwyb)

代码位于：https://github.com/tuna/THU-Beamer-Theme.git



当前版本：

对block配色进行了些许修改，对引用的style进行了一定修改。



注意：

用vscode直接编译会有参考文献不显示的问题，解决方案如下：

在写完ref.bib后运行tex文件，生成aux文件

在终端运行：`bibtex xxx.aux`生成 bbl文件

再次运行tex文件，生成完整的pdf



问题：

在本地vscode运行有参考文献在bbl中的\newblock指令下自动换行的问题，仍然没有解决。

目前比较笨拙的解决方案是：手动删除bbl中的\newblock



