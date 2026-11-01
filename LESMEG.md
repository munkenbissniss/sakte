# Sakte – AI slow motion

Webapp som lager slow motion med AI (RIFE 4.6) direkte på mobilen eller PC-en.
Videoen forlater aldri enheten.

## Legg den på nett (gratis, ca. 3 minutter)

**GitHub Pages**
1. Lag et nytt offentlig repo på github.com, f.eks. `sakte`.
2. «Add file → Upload files» og dra inn alle filene i denne mappen.
3. Settings → Pages → Source: «Deploy from a branch», branch `main`, mappe `/ (root)`.
4. Etter et minutt ligger appen på `https://<brukernavn>.github.io/sakte/`.

**Netlify Drop** (uten konto i starten): gå til app.netlify.com/drop på en PC og dra mappen inn.

Lokalt på PC: `python3 -m http.server 8000` i mappen og åpne http://localhost:8000

## På mobilen
Åpne adressen → Del → «Legg til på Hjem-skjerm» (iPhone) / «Installer app» (Android).
Etter første gang fungerer den også uten nett.

## Krav
- iPhone/iPad: iOS 17 eller nyere (iOS 26 gir GPU-akselerasjon via WebGPU)
- Android/PC: nyere Chrome, Edge eller Firefox
- Korte klipp (2–10 s) anbefales på mobil. 480p går raskest.
