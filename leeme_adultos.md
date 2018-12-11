``` /home/hp/Mis_aplicaciones/pandoc-2.5/bin/pandoc -t revealjs -s -o adultos.html adultos.md --from markdown+fenced_divs -V revealjs-url=./reveal.js -V theme=my_white
/home/hp/Mis_aplicaciones/pandoc-2.5/bin/pandoc -t revealjs -s -o cledu.html cledu.md --from markdown+fenced_divs -V revealjs-url=./reveal.js -V theme=my_white
```

Pandoc 1.9 no tiene la extensión *fenced_divs* para notas y columnas, por eso hay que ejecutar *pandoc-2.5*. Esa extensión permite añadir notas al orador, pausas, etc.