# latex_user
### 使用前配置
- texmaker安装（ubuntu软件官方安装）
- sudo apt-get install texlive-xetex （为了使用xelatex）
- sudo apt-get install latex-cjk-all  (为了使用xeCJK输出中文pdf)
- 修改texmaker使用xelatex编译
- 下面是例程
---
\documentclass{article}

\usepackage{xeCJK}

\begin{document}

爱你，森森

\end{document}

---
### 论文编辑
- git clone https://github.com/TingliangZhang/XeLatexTemplate-ztl (下载模板)
- 在texmaker上打开配置-命令-xelatex框中加入--shell-escape　如图 
- ![figure1](https://github.com/wy7727/latex_user/blob/master/figure/2019-09-27%2002-24-49%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE.png)

### latex使用技巧

##### 公式
- 引用公式在正文前加\usepackage{amsmath}
- 引用百分号　$\%$


##### 列表
- 带序号列表为：
\begin{enumerate}[step 1]

\item good morning...

\item good morning....

\end{enumerate}

- 无序号列表为：
\begin{itemize}

\item[-] good morning...

\item[-] good morning....

\end{itemize}

#### 公式
- \begin{equation}
r_K(X_i,Y_i) \triangleq \dfrac{\sum\limits^n_{i=1}\sum\limits^n_{j=1} sgn\left( X_i-X_j\right) sgn\left( Y_i-Ｙ_j\right)}{n\left(n-1\right)} 
\end{equation}
- 公式编号
- $$公式行间$$
- $公式嵌入$
#### 错误
- ! Undefined control sequence.一般是缺少相应的package
