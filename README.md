# LaTeX-packages

My personal LaTeX and Beamer setup, with all the packages I use on a regular basis.

To use it, first download the repository to a location `PATH`. Then, to create a LaTeX document, you just need the following structure:

```latex
\documentclass{article}

\input{PATH/packages.tex}
\input{PATH/notations.tex}
\input{PATH/doc_setup.tex}
\addbibresource{sources.bib}

\begin{document}

...

\end{document}
```

whereas for a Beamer presentation, you would use:

```latex
\documentclass{beamer}

\input{PATH/packages.tex}
\input{PATH/notations.tex}
\input{PATH/beamer_setup.tex}
\addbibresource{sources.bib}

\begin{document}

...

\end{document}
```