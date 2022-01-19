# Quantum Algorithms Spring'22, IIIT Hyderabad

Course taken by Prof. Shantanav Chakraborty.

TA: Aditya Morolia (Moi!)

## Scribe Builds

![Build paper](../../workflows/Build Paper/badge.svg)

- [Lecture 1](../../raw/build/lecture_1.pdf)
- [Lecture 2](../../raw/build/lecture_2.pdf)

## Instructions for students

Make a PR with your scribe sources. Follow the following structure:

- The folder named `Lecture_X` is the scribe template to be used.
- If you are scribing lecture `X`, all your source files should be in one folder named `Lecture_X` in the *root* directory.
- The main file should be named `lecture_X.tex`
- Put all your images into an `images` folder inside your folder.
- You may use the `preamble.tex` if you wish to.

## Template to use the preamble

```tex
\documentclass[11.5pt, paper=a4]{article}


\usepackage{preamble}

\begin{document}

\maketitle
\tableofcontents

%% Add appropriate bib info

\end{document}

```



## Locally building tex

### Recommended packages to install

`sudo pacman -S texlive-most texlive-core texlive-science texlive-latexextra texlive-bibtexextra texlive-publishers`

### Edit

Use favourite editor to edit.
PS: Check out https://github.com/lervag/vimtex#requirements

### To Build

`latexmk -pdflatex filename.tex`


