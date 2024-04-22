# This template was created by Ta Viet Tai, ICTLAB, FETEL, VNU-HCM University of Science.

This template was created based on the standards of the 2020 graduation thesis of master students at the VNU-HCM University of Science. 
The content in the template is for reference only. The template supports both Vietnamese and English. To use English, please comment `\usepackage[vietnamese]{babel}` in `Thesis.tex` file.

## The thesis formatting

The format of the thesis (title, subtitle, thesis information, etc.) was created in `doctorvn.sty` file. If you want to modify some format, you can modify this in `doctorvn.sty`.

## The bibliography

The bibliography of this thesis was automatically created and you must put all of the references as `.bib` format in `./0-bib/Bib_Reference.bib`

If you have several publications, please add them manually at the end of `Thesis.tex` file

## The figures and tables

This template supports the Tikz picture, you can learn how to use the Tikz picture at [Tikz.org](https://tikz.org/) or [Tikz.dev](https://tikz.dev/)

> [!TIP]
> In case you have too many Tikz images, you can convert it to PDF and then use it as an image, which will save a lot of compilation time. You can do this by using 
``` 
pdflatex -shell-escape <mainfile>.tex 
```

> [!Important]
> You must make sure the `fig_tikz` folder is empty and before converting the image, you must comment `\maketitlepage` and comment the code to make the watermark in the `Thesis.tex` file.

## [The Glossary](https://www.overleaf.com/learn/latex/Glossaries)

The acronyms are defined in `glossary.tex` file. Adding new acronym, using `\newacronym{label}{Acrnonym}{Full name}`
Example: 
```
\newacronym{tcp}{TCP}{Transmission Control Protocol}
```
The display of the acronym
```
\acrfull{tcp}  --> "Transmission Control Protocol (TCP)"
\acrlong{tcp}  --> "Transmission Control Protocol"
\acrshort{tcp} --> "TCP"
```

## Acknowledge
To know more and contribute to the sample, please contact me via [tvtai@hcmus.edu.vn](tvtai@hcmus.edu.vn)