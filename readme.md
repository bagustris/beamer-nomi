## Installation

Move all files in this repository to ~/texmf/tex/latex/beamer:
~~~
$ mkdir -p ~/texmf/tex/latex/beamer
$ cp *.sty ~/texmf/tex/latex/beamer
~~~

## Compilation
~~~
$ cd example
$ pdflatex beamer_16.9.tex
~~~

## Changelog
- 2020/11/05: Add an example for 16:9 aspect ratio (example/beamer_169.tex)
- 2018/5/24 : modify beamerinnertheme.sty to fit jaist logo
- 2018/8/5  : modify beamerouterthemedecolines.sty to place
              page count inside box
- 2018/9/22 : add example
