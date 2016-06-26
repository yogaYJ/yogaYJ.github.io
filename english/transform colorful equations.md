<script type="text/x-mathjax-config">
  MathJax.Hub.Config({ TeX: { extensions: ["color.js"] }});
</script>

<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>

# 色彩标注法

Stuart Riffle 曾给出过一个傅立叶变换的绝妙解释。在他的文章中有大量精彩的图片，但其中最精妙的莫过于他关于离散傅立叶逆变换公式的解释： 

![Mou icon](figure1.png)

多么精彩的演示啊！我的第一个想法就是应该有更多的方程式采用这种优雅的、专注于读者理解的解释方法。我希望能够以这种方法给出清晰的解释。 

$$\textcolor{Purple}{X}_\textcolor{Green}{k}
=\textcolor{Magenta}{\frac{1}{N}\sum_{n=0}^{N-1}}
\textcolor{Blue}{x_n}
\textcolor{Red}{e}^
{\textcolor{Red}{i}\textcolor{Orange}{2\pi} 
\textcolor{Green}{k}
\textcolor{Magenta}{\frac{n}{N}}
}.$$
**为了发现<font color=Green>在特定频率下</font><font color=Purple>的能量</font>，<font color=Green>以那个频率</font><font color=Orange>环绕一圈</font><font color=Red>来旋转</font><font color=Blue>你的信号</font>，并且<font color=Magenta>沿着该路径平均地分配一束点</font>。**
**与机械化翻译公式的结合：**在翻译长难句时，由于句子非常长，我们往往看不清句子的层次，因此导致了翻译的困难。从傅立叶公式的例子来看，色彩标注法的思想是通过不同颜色的标注来分析傅立叶公式的结构，清晰地划分出各个因子在公式中的位置和作用。这个方法可以运用到长难句翻译中：将句子的不同成分用不同的颜色进行标注，例如用一种颜色标注出句子的主干部分，然后用其他的不同颜色分别标注句中的状语、定语、同位语等等。通过不同的颜色划分，更清晰的展示出句子中有哪些成分，一目了然的看出句子层次，有利于对句子的细致分析，最后运用机械化翻译公式，按照中英文的不同逻辑，以倒序和并列不变序为两大原则，将英语句子合理的翻译为中文。

**Remark:**

1. Html color setting  
		<font color=Blue>Blue</font> 
		 <font color=Brown>Brown</font> 
		 <font color=Cyan>Cyan</font> 
		 <font color=Green>Green</font> 
		 <font color=Grey>Grey</font> 
		 <font color=Magenta>Magenta</font> 
		 <font color=Orange>Orange</font> 
		 <font color=Yellow>Yellow</font> 
		 <font color=Purple>Purple</font> 
2. The raw equation is $$X_k=\frac{1}{N}\sum_{n=0}^{N-1}x_ne^{i2\pi k \frac{n}{N}}.$$
3. Reference: [Colorful Equations With MathJax](http://adereth.github.io/blog/2013/11/29/colorful-equations/)