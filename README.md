# PelargoniumWorld Photo Tool

Готов статичен GitHub Pages инструмент за обработка на снимки. Всичко работи client-side.

## Важно
`index.html` е самостоятелен и съдържа CSS, JavaScript и копие на оригиналното PelargoniumWorld PNG лого. Така инструментът не зависи от относителни CSS/JS/asset пътища и не се чупи при публикуване в GitHub Pages.

## GitHub Pages
1. Качи **съдържанието на тази папка** в root на repository-то (така че `index.html` да е в root).
2. GitHub → Settings → Pages.
3. Source: Deploy from a branch.
4. Branch: main, folder: / (root).
5. Save.

Ако repository-то е `PelargoniumWorld-photo-tool` на потребител `USERNAME`, URL адресът ще бъде:
`https://USERNAME.github.io/PelargoniumWorld-photo-tool/`

## Локално
Може да отвориш `index.html` директно или да стартираш:

```bash
python3 -m http.server 8000
```

После: http://localhost:8000
