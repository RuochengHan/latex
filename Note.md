1. When using minipage, do not leave any lines between \end{minipage} and \begin{minipage}:
```latex
\end{minipage}
\begin{minipage}

%%% or
\end{minipage}
\
\begin{minipage}
```

2. Change section style:
```latex
\renewcommand \thesection{S\arabic{section}}
```
