# Note of Winter Vacation 2020 --- English Version ReadMe
 Note typeset by LaTeX
 
## Known Issues:
### Badbox
I used "\sloppypar", line break and other techniques to eliminate all "Overfull hbox"es, but
some of them then became "Underfull hbox"es. I won't resolve them until I find some better ways.

## How to Compile
This documentation uses BIBTeX to generate bibliography, hyperref to generate hyperlinks, and due to some other reasons,
the compile order should be like this:
1. Run pdflatex Main.tex
2. Run bibtex Main.tex
3. Run pdflatex Main.tex multiple times until **warnings like "Main.out has changed" no longer occurs**.

# 2020寒假笔记 --- 简体中文版ReadMe
由LaTeX排版的笔记
 
## 已知问题:
### Badbox
我使用了 "\sloppypar", 换行和其它的一些手段来消灭一切"Overfull hbox", 然而
它们中的一些成为了"Underfull hbox"。 我不会在这个问题上进一步费时间除非我找到了一些更好的方法。

## 怎么编译
由于这文档使用了 BIBTeX 来生成参考文献， hyperref来生成pdf里的hyperlinks，和别的一些原因， 所以编译顺序要像下面一样:
1. 运行 pdflatex Main.tex
2. 运行 bibtex Main.tex
3. 运行 pdflatex Main.tex 多次直到**像"Main.out has changed"这样的警告不再出现**. 