# Poliklinika Materna – sajt

Statički sajt u jednom fajlu (`index.html`). Nema build koraka.

## Objavljivanje na GitHub Pages
1. Napravite novi repozitorijum na github.com (npr. `materna-sajt`).
2. Add file → Upload files → prevucite `index.html` i `.nojekyll` → Commit.
3. Settings → Pages → Source: *Deploy from a branch*, Branch: `main` / `(root)` → Save.
4. Sajt je na `https://<korisnik>.github.io/materna-sajt/` za 1–2 minuta.

## Sopstveni domen (npr. materna.rs)
Settings → Pages → Custom domain → `www.materna.rs`. Kod registra domena dodajte CNAME zapis `www` → `<korisnik>.github.io`.

## Pre puštanja u rad
- Fotografije lekara i usluga se učitavaju sa `www.materna.rs/images/`. Ako se stari sajt ugasi, preuzmite slike u repozitorijum.
- Forma za zakazivanje bez podešenog endpointa otvara email program pacijenta (ordinacija@materna.rs). Za direktno slanje napravite besplatnu formu na formspree.io i URL upišite u `formEndpoint`, pa ponovo izvezite sajt.
- Proverite podatke označene sa „potvrditi“ i „primer cene“, pa isključite oznake.
