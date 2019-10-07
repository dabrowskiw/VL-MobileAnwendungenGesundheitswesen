# VL-MobileAnwendungenGesundheitswesen

## Compilation

Die Präsentation ist in LaTeX unter Verwendung des Pakets beamer geschrieben. Vorsicht: Die Bibliographie in beamer funktioniert nicht mit bibtex sondern mit biber, also bitte wie folgt bauen:

```sh
pdflatex slides.tex
biber slides
pdflatex slides.tex
```
