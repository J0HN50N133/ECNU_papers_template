## 模板说明

本模板主要适用于一些课程的平时论文以及期末论文，默认页边距为2.5cm，中文宋体，英文Times New Roman，字号为12pt（小四）。

编译方式：`xelatex -> bibtex -> xelatex*2`

默认模板文件由以下四部分组成：

<!-- more -->

1. `main.tex` 主文件
2. `reference.bib` 参考文献，使用bibtex
3. `ECNUpapers.sty` 文档格式控制，包括一些基础的设置，如页眉、标题、姓名等
4. `figures` 放置图片的文件夹

第一次使用时需前往`ECNUpapers.sty` 对标题、姓名、学号、院系、页眉等进行设置，设置完后即可一劳永逸，封面logo亦可替换

默认带有封面页以及目录页，页码从目录页开始

## 特色功能

1. 智能引用`\autoref{}`
2. 插入圆角灰底的文本框`\tbox{}`
3. 中文定理环境
4. Bibtex

## 鸣谢

本模板Fork自：

- [GitHub：https://github.com/LeyuDame/BNUpapers](https://github.com/LeyuDame/BNUpapers)
