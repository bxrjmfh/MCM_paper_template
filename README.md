## README

图片放置在该文件目录下，参考文献放置于books.bib中，表格图片等的使用详情查看上一级文件目录中的相应板块

### 快捷的指令
    1.new command : latex 内置
    \newcommand\s[1]{\textbf{\section{#1}}}
    \newcommand\subs[1]{\textbf{\subsection{#1}}}
    \newcommand\subss[1]{\textbf{\subsubsection{#1}}
    大中小标题

    \newcommand\pic{\centerline{\textcolor{red}{picture！}}}
    缺失标题的填充

### 基本语法

    \begin{itemize}
    \item 123
    \item 234
    \end{itemize}
    创建无序列表

    \begin{enumerate}
    \item 123
    \item 234
    \end{enumerate}
    有序列表

    \vspace*{10pt}
    使用此来调节行间距

    \cite{} 
    进行文献的引用





### memo的添加：

![3](assert/3.png)
    使用create_a_memo_...指令创建新的信件，记得切换下一个页面。

### 公式的添加：
![4](assert/2022-02-05_221735.png)
    添加公式，不需要加$$

### 图片的添加：

    1. 子图的添加：
 使用create_subpicture添加一个包含子图的图片，效果如下：
 ![09](assert/2022-02-06_165536.png)

    可以在subfigure之后添加\\对图片的排版进行控制，需要添加多张子图可以使用指令add_sub进行处理。
![d](assert/2022-02-06_170254.png)

    2. 一般图片的添加：
   使用create_pic 添加单张图片，效果如下：
![es](assert/2022-02-06_165801.png)
   
