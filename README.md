# COSSIG-Documentations
> 这个储存库负责保存本社区各类 PDF 格式官方文档的 LaTeX 源代码。

README 文件更新时间：2023 年 1 月 4 日

储存库目前内容：[COSSIG 文档样式标准](./documentation-regulations.tex) （非完整版本）<br/>
计划中要编写的内容：COSSIG 贡献指南 1.0（目前的[贡献指南](github.com/COSSIG/Mission-Control/blob/main/README.md)为非正式版）

目前没有正式发布的 PDF 文档。

因为[社区美工，即本储存库目前的主要维护者](github.com/Northurland) TeX 不熟练，所以这里的代码可能会看起来很蠢。

编译本储存库中的内容：<br/>
\*因为我对 LaTeX 的了解非常少，所以只能提供一些个人编译时不知道是否关键的基础信息。-- Northurland

本人使用的操作系统：Windows 10 21H2<br/>
本人使用的 TeX 发行版：TeX Live<br/>

使用 XeLaTeX 直接输出 PDF 格式文件，命令如下：<br/>
`xelatex documentation-regulations.tex`

如果正确运行，以上的命令会输出文件名为“documentation-regulations”，标题为“COSSIG 文档样式标准”的 PDF 文件。请不要直接编译 documentation-styles.tex，因为其中没有正文。

请在编译之前保证自己安装了[本储存库中的字体](./fonts/)。已知的问题：如果在 Windows 中安装了字体，但被提示无法找到字体的话，请确保自己点选“为所有用户安装”（需要管理员权限）选项。
