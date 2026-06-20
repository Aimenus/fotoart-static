# FotoArt Studio – Statyczna strona HTML

Strona zoptymalizowana pod SEO dla studia fotograficznego FotoArt Studio.
Stworzona jako część pracy licencjackiej – implementacja statyczna HTML/CSS.

## Jak wdrożyć na GitHub Pages

1. Utwórz nowe repozytorium na GitHub (np. `fotoart-static`)
2. Wrzuć wszystkie pliki do repozytorium
3. Wejdź w Settings → Pages → Source: Deploy from branch → main → / (root)
4. Po chwili strona będzie dostępna pod: `https://TWOJA-NAZWA.github.io/fotoart-static/`
5. **WAŻNE:** Po wdrożeniu zaktualizuj canonical URL we wszystkich plikach HTML:
   - Zmień `https://fotoartstudio.github.io/` na swój faktyczny URL
   - Zaktualizuj też URL w sitemap.xml

## Zastosowane techniki SEO

- Semantyczna struktura HTML5 (header, main, article, section, footer, nav)
- Unikalny tag `<title>` na każdej podstronie
- Meta description z słowami kluczowymi
- Meta robots: index, follow
- Tag canonical (rel="canonical")
- Open Graph (og:title, og:description, og:image, og:type, og:locale)
- Twitter Card (summary_large_image)
- Dane strukturalne JSON-LD (LocalBusiness, BreadcrumbList, Service, ImageGallery)
- Atrybut lang="pl" na elemencie <html>
- Alt text na wszystkich obrazach
- Meta viewport (responsywność)
- robots.txt
- sitemap.xml
- Breadcrumb nawigacja
- ARIA labels dla dostępności

## Struktura plików

```
fotoart-static/
├── index.html      – Strona główna
├── portfolio.html  – Galeria zdjęć
├── uslugi.html     – Usługi i cennik
├── kontakt.html    – Formularz kontaktowy
├── style.css       – Arkusz styli
├── robots.txt      – Instrukcje dla robotów
├── sitemap.xml     – Mapa witryny
└── README.md       – Ten plik
```
