---
title: w5NjKC
permalink: w5NjKC
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
\newtheorem{thm}{Théorème}[section]
\newtheorem{coro}{Corollaire}[thm]
\renewcommand{\thecoro}{
  \arabic{section}.\arabic{thm}.\Alph{coro}}

\section{Élements}
\begin{thm}  Texte. \end{thm}
\begin{coro} Texte. \end{coro}
\begin{coro} Texte. \end{coro}
\begin{thm}  Texte. \end{thm}
\begin{coro} Texte. \end{coro}
```