# 2024sdu-latex-undergraduate
2024山东大学本科毕设Latex模板

当你需要生成完整的论文时，请使用xelatex 。在该环境下，你生成的新章节应使用\input指令。

在攥写过程中，建议使用pdflatex，这样更快，但也缺少对中文字体和参考文献的支持。建议使用\include插入你的章节。在合理的位置使用
指令组 \ifxelatex 和 \fi 可使你的论文攥写更顺畅。

你可以下载论文官网提供的bibtex，将其内容复制到ref.bib中管理参考文献。

最后，友谊就是魔法！
