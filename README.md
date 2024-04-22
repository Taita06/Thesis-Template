# This template was created by Ta Viet Tai, ICTLAB, FETEL, VNU-HCM University of Science.

## The thesis formating

The format of the thesis (title, subtitle, thesis information, etc.) are created in `doctorvn.sty` file. If you want to modify some format, you can modify this in `doctorvn.sty`.

## The thebibliography

The thebibliography of this theis was automatic created and you much put all of references as `.bib` format in `./0-bib/Bib_Reference.bib`

If you have several publication, please adding it manually in the end of `Thesis.tex` file

## The figures and tables

This template support tikz picture, you can learn how to use tikz picture at [Tikz.org](https://tikz.org/) or [Tikz.dev](https://tikz.dev/)

> [!TIP]
> In case you have too many Tikz images, you can convert it to pdf and then use it as an image, which will save a lot of compilation time. You can do this by using 
``` pdflatex -shell-escape <mainfile>.tex ```

> [!Warning]
> You must make sure the fig_tikz folder is empty and before converting the image, you must comment `\maketitlepage` and comment the code make the water mark in `Thesis.tex` file.
