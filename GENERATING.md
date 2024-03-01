### To make the HTML
```
pandoc README.md -f markdown -t html -c style.css -s -o resume.html
```

### To make the PDF
```
pandoc README.md -f markdown -t pdf --pdf-engine=wkhtmltopdf -c style.css -s -o resume.pdf
```

### Acknowledgements
- https://luther.io/projects/markdown-resume/