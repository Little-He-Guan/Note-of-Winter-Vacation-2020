# Note of Winter Vacation 2020 --- English Version ReadMe
 Note typeset by LaTeX
 
## Known Issues:
### Badbox
I used "\sloppypar", line break and other techniques to eliminate all "Overfull hbox"es,
but
* some of them then became "Underfull hbox"es;
* there is still one, but Texmaker tells me it's in the preamble, and I don't know why.
I won't resolve them until I find some better ways
### Incorrect bold character
At the beginning of some paragraphs, the first character unexpectedly becomes bold.
I don't understand exactly how it occurs, but I think that
this is probably a problem of the package "ctex", which I use to support chinese characters in LaTeX.

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
* 它们中的一些成为了"Underfull hbox"；
* 还有一个Overfull hbox，但是Texmake告诉我它在preamble里，我不知道这是为什么。
我不会在这个问题上进一步费时间除非我找到了一些更好的方法。
### 错误的粗体字
在一些段落的开头，第一个字符未被预料地变成了粗体。
我不是很确定这问题是怎么出现的，但是我猜它很可能是因为我用来在LaTeX里支持中文字符的
宏包"ctex"导致的。

## 怎么编译
由于这文档使用了 BIBTeX 来生成参考文献， hyperref来生成pdf里的hyperlinks，和别的一些原因， 所以编译顺序要像下面一样:
1. 运行 pdflatex Main.tex
2. 运行 bibtex Main.tex
3. 运行 pdflatex Main.tex 多次直到**像"Main.out has changed"这样的警告不再出现**. 