# Kantine nettside

jeg lagde dette med flask til kantina for akademiet.
## Sidene

- Hjem: ønsker velkommen til brukere når de går inn på siden.
- Meny: viser menyen som er ukens meny fra mandag til fredag.
- Varer: varer som viser pris og det som er på menyen.
- Kontakt: telefon, e-post og åpningstider.

## Om koden

I app.py har jeg en rute for hver side. Menyen og varene ligger som lister i kantinedata.py og vises med for-løkker. Alle sidene arver fra base.html, som har toppmenyen og bunnteksten. Designet ligger i static/style.css.

## Kjøre prosjektet

Installer Flask med pip install flask, kjør app.py og åpne http://127.0.0.1:5000 i nettleseren.

Laget av Jeppe
