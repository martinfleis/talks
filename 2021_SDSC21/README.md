To build the slides:

```
pandoc \
    --section-divs \
    -t revealjs \
    -s \
    --metadata title="Capturing the Structure of Cities with Data Science" \
    --variable theme="ugai" \
    --template template.revealjs \
    -o intro.html \
    intro.md
```