在**library**目录下找到**rmarkdown**文件夹，然后是**rmd**、**latex**，在default.tex文件中国找到`\begin{document}`，在其之前加入
```tex
\usepackage{ctex}
\setmainfont{SimSun}
```
