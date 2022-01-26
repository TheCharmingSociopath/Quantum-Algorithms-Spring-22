# Quantum Algorithms Spring'22, IIIT Hyderabad

### A team of two students taking the cource scribe each lecture for the [course](https://sites.google.com/view/shchakra/teaching/s22-quantum-algorithms). 

Course taught by [Prof. Shantanav Chakraborty](https://sites.google.com/view/shchakra/).

TA: [Aditya Morolia (Moi!)](https://thecharmingsociopath.github.io/)

#### Disclaimer: Most scribes here are a work in progress and the documents should be treated as such. These will be finished by the end of the course. 

## Scribe Builds

![Build](../../workflows/Build%20Scribes/badge.svg)

- [Template](../../raw/build/lecture_X.pdf)
- [Lecture 1](../../raw/build/lecture_1.pdf)
- [Lecture 2](../../raw/build/lecture_2.pdf)
- [Lecture 3](../../raw/build/lecture_3.pdf)
- [Lecture 4](../../raw/build/lecture_4.pdf)

## Instructions for students

Make a PR with your scribe sources. Follow the following structure:

- The folder named `Lecture_X` is the scribe template to be used.
- If you are scribing lecture `X`, all your source files should be in one folder named `Lecture_X` in the *root* directory.
- The main file should be named `lecture_X.tex`
- Put all your images into an `images` folder inside your folder.
- You may use the `preamble.tex` if you wish to.
- Update README with the scribe build (just copy one of the previous lines) for your notes. It'll give you a direct download link to view and read the scribes.
- Build scribe runs on each push. 

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



## Locally building tex documents (Arch)

Debian instructions similar, use `apt-get` to install.  

### Recommended packages to install

`sudo pacman -S texlive-most texlive-core texlive-science texlive-latexextra texlive-bibtexextra texlive-publishers`

### Make your edits to a .tex file 

Use favourite editor to scribe.
PS: Check out https://castel.dev/post/lecture-notes-1/ (Vim is beautiful)

### To Build

`latexmk -pdflatex filename.tex`


