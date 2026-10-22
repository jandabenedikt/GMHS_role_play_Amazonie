# Amazonie ve faktech

Přehledová aplikace do zeměpisu: 81 faktů o kácení deštných pralesů v brazilské Amazonii, seřazených do 11 témat, s vyhledáváním napříč fakty. Stav k 22. 10. 2026, u každého údaje je odkaz na zdroj.

## Obsah

- `index.html` – celá aplikace v jednom souboru (data jsou přímo v něm, z internetu se načítají jen písma Google Fonts)
- `soupis-faktu-amazonie.pdf` – stejná fakta k tisku (4 strany A4)
- `.nojekyll` – urychlí zveřejnění na GitHub Pages (není nutný)

## Zveřejnění přes GitHub Pages

1. Vytvořte nový veřejný repozitář, např. `amazonie-fakta`.
2. Nahrajte soubory z této složky do kořene repozitáře (*Add file → Upload files*).
3. *Settings → Pages* → *Deploy from a branch*, větev `main`, složka `/ (root)` → *Save*.
4. Za 1–2 minuty bude aplikace na `https://<uživatel>.github.io/amazonie-fakta/`.

## Přímé odkazy na témata

Na konec adresy připište `#` a název tématu:

`#amazonie-a-odlesnovani` · `#klima-a-bod-zvratu` · `#sucha-a-zivot-ve-mestech` · `#zemedelstvi-a-dobytek` · `#sojove-moratorium-a-obchod` · `#tezba-a-zlato` · `#puvodni-obyvatele` · `#zakony-a-politika` · `#doprava-ropa-a-velke-stavby` · `#penize-za-ochranu-lesa` · `#priklady-ze-zahranici`

## Ovládání

- Šipky vlevo/vpravo přepínají témata, Esc vrací na přehled témat.
- Klávesa `/` skočí do vyhledávání; hledání nerozlišuje diakritiku.
