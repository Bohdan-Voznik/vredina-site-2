============================================================
PROJECT: Arnold Bode im crossmedialen Viewport
============================================================

A) PROJEKTINFOS
----------------
PROJECT_TITLE: "Arnold Bode im crossmedialen Viewport"
DOMAIN: [DOMAIN_OHNE_HTTPS]

Farben (CFG):
- PRIMARY_COLOR: [#HEX]
- SECONDARY_COLOR: [#HEX]
Neutrals: weiß/schwarz/grau sind erlaubt (Akzente nur Primary/Secondary)

Font (Google Webfont, CFG):
- GOOGLE_FONT_FAMILY: [FONTNAME]
- FONT_FALLBACK: system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif

Dateien:
- index.html
- styles.css
- app.js
- readme.txt
- img/ (Ordner vorhanden)
  - img/01.jpg ... img/06.jpg

Bildpfade (relativ, wie im Projekt verwendet):
- img/01.jpg
- img/02.jpg
- img/03.jpg
- img/04.jpg
- img/05.jpg
- img/06.jpg

Start:
- index.html im Browser öffnen (lokal oder über beliebigen Static-Server).


B) KUNSTWERK / STILMITTEL
-------------------------
ARTWORK_REFERENCE_TITLE:
- "documenta 1 – Briefmarke Arnold Bode"

Übertragene Prinzipien (nicht 1:1 kopiert):
- Asymmetrie: Content + Gegengewicht als zweites Panel
- Kontrast: PRIMARY_COLOR vs. S/W-Fläche auf Weißraum
- Dominantes Zeichen: übergroßes „d“ als Hauptform im Hero
- Perforation-Anmutung: gestrichelter Rahmen im Panel
- Typografie: ruhig, klare Hierarchie, gut lesbar

Regeln (CFG) eingehalten:
- Nicht 1:1 kopieren, sondern Prinzipien übertragen
- Akzentfarben nur über PRIMARY_COLOR und SECONDARY_COLOR
- Mengentext ruhig, klare Hierarchie, hohe Lesbarkeit


C) TECHNIK / FEATURES
---------------------
HTML:
- semantische Struktur: <header>, <main>, <section>, <footer>
- Navigation mit Anchor Links: #about, #timeline, #gallery
- Textlogo + kleines Signet per CSS

CSS:
- :root Variablen + clamp() für Typo
- Basis-Grid/Flex, einfache Breakpoints
- Fokuszustände (:focus-visible), wenig Spezifität

JS (reduziert):
- optionaler Smooth-Scroll für Anchor Links
- keine Galerie-Vergrößerung / keine Lightbox


D) VERWENDETE SOFTWARE / TOOLS
------------------------------
- Editor/IDE: Visual Studio Code (oder vergleichbar)
- Browser: Chrome / Firefox / Safari (Tests empfohlen)

E) VERWENDETES KI-MODELL
------------------------
- OpenAI ChatGPT — Modell: GPT-5.2 Thinking
