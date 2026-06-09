Bistro U Vr2le — web (návrh)
================================

Tahle složka je připravená k nasazení na statický hosting
(Netlify, GitHub Pages, Vercel...). Vstupní soubor je index.html.

Obsah:
  index.html        – samotný web
  assets/logo.jpg   – logo
  image-slot.js     – komponenta pro fotky

-------------------------------------------------
NASAZENÍ PŘES NETLIFY (nejrychlejší cesta)
-------------------------------------------------
A) Drag & drop (bez GitHubu):
   1. Jdi na https://app.netlify.com/drop
   2. Přetáhni SEM celou tuhle složku (nebo rozbalený zip).
   3. Hotovo — Netlify ti dá veřejnou adresu.

B) Přes GitHub:
   1. Nahraj obsah složky do repozitáře na GitHubu.
   2. V Netlify: Add new site -> Import from Git -> vyber repo.
   3. Build command nech prázdný, Publish directory = / (kořen).
   4. Deploy.

-------------------------------------------------
FOTKY
-------------------------------------------------
Místa pro fotky (hero + galerie) jsou zatím prázdné placeholdery.
Až budeš mít reálné fotky, dej vědět a vyměním placeholdery
za normální obrázky (stačí je nahrát do složky assets/).

-------------------------------------------------
CO JEŠTĚ DOPLNIT
-------------------------------------------------
- reálný jídelní lístek (teď jsou tam ukázkové položky)
- odkazy na Facebook / Instagram (teď vedou na "#")
