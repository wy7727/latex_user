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
