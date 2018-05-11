# LaTeX Template for Chinese

一个符合中文排版要求的 LaTeX 样式模板

## Demo

[http://latex.joway.io/](http://latex.joway.io/)

## Usage

1. 下载 zhtypo.sty 样式文件 [http://latex.joway.io/styles/zhtypo.sty](http://latex.joway.io/styles/zhtypo.sty)
2. 引入 sty 文件 , 样例参见 template.tex 文件

	```tex
	\documentclass[12pt]{article}
    \usepackage{styles/zhtypo}
	
    \title{LaTeX 介绍}
    \author{维基百科}
    \date{\today}
	
    \begin{document}
    \maketitle
    
    % ...
    
    \end{document}
	```

3. 默认使用:
	- 冬青字体
	- 1.5倍行间距
	- 0.5 baseline 段间距