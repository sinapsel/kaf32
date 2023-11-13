# kaf32
Website for Department of Theoretical Physics (#32) NRNU MEPhI

[GitHub Page Deployment Demo](https://sinapsel.github.io/kaf32/)

Created with SSG [HUGO](https://github.com/gohugoio/hugo) [v0.120.3](https://github.com/gohugoio/hugo/releases/download/v0.120.3/hugo_0.120.3_linux-amd64.tar.gz)
The theme is based on [Mainroad](https://github.com/Vimux/Mainroad).

Some extra features:
- Adaptive menu: left sidebar on large screens turns into nav-bar burger on small smartphones
- JSON-based static search
- Language switcher
- MathJax support
- Raw HTML injection snippet


Development build:
```bash
hugo server --buildDrafts --noHTTPCache --disableFastRender --gc                                                                  
```

Production build
```bash
hugo --baseURL=\'$BASE\'
mv public/index.json public/map.js
mv public/ru/index.json public/ru/map.js
```
