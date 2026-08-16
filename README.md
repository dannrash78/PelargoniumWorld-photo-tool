# PelargoniumWorld Photo Tool

Готов browser-only инструмент за персонализиране на снимки с логото на PelargoniumWorld.

## Функции

- локален upload на снимка — снимката не се изпраща към сървър;
- live canvas preview;
- drag & drop на снимката, логото, watermark-а и текста;
- zoom, X/Y позиция и rotation на снимката;
- оригиналното PelargoniumWorld PNG лого като графичен asset;
- размер, прозрачност, позиция и rotation на логото;
- PNG/SVG/WebP watermark;
- персонален текст с шрифт, размер, bold, italic, цвят, прозрачност и подравняване;
- режим „Надпис под снимката“;
- presets: 1:1 кръг, Facebook Square, Facebook Portrait 4:5, Landscape 16:9, Website, Original, Custom;
- PNG/JPG export;
- JPG quality;
- прозрачен PNG фон или цветен фон;
- Undo / Redo / Reset;
- mobile/touch pointer events;
- без backend и без външни библиотеки.

## Локално стартиране

Може да се отвори и директно с `index.html`, но за най-надежден тест използвай локален HTTP server:

```bash
python3 -m http.server 8000
```

После отвори `http://localhost:8000`.

## GitHub Pages

1. Създай нов GitHub repository.
2. Качи всички файлове и папки от този проект в root на repository-то.
3. В GitHub: **Settings → Pages**.
4. Избери **Deploy from a branch**.
5. Избери `main` и `/ (root)`.
6. Save.

Публичният адрес обикновено е:

`https://USERNAME.github.io/REPOSITORY-NAME/`

## Важно за логото

`assets/pelargoniumworld-logo.png` е използвано директно като графичен asset. Инструментът не пресъздава логото с HTML текст, CSS шрифтове или AI.
