# aten.sty

`aten.sty` provides a simple and lightweight solution to make your LaTeX documents prettier.

## How to use

When creating a new document, use the following starter:
```latex
\documentclass{article}
\usepackage{aten}

\newcommand{\documenttitle}{DOCUMENT TITLE}
\newcommand{\authorname}{AUTHOR NAME}

\begin{document}

\title{\documenttitle}
\rhead{\textbf{\small \documenttitle}}
\lhead{\textbf{\small \authorname}}
\author{\authorname}
\maketitle

\tableofcontents
\newpage

% Content goes here

\end{document}
```

## Attribution

Attribution is not needed on the pdfs generated, although it would be nice. 
