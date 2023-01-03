## To re-generate pdf
```bash
pandoc Markdown/README.md --to=pdf -t latex -o resume.pdf --pdf-engine=xelatex -V geometry:"top=1cm, bottom=0cm, left=1cm, right=1cm" -V colorlinks=true -V linkcolor=blue
```