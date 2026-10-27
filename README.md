# 💡 Ideeën Vault

Al je ideeën veilig op één plek. Een simpele app die werkt in de browser van je telefoon of computer, zonder account, zonder AI en zonder kosten.

## Wat kan de app?

- Ideeën opslaan met titel, uitleg, categorie, sterren (1–5) en tags
- Status bijhouden: 💡 Idee, 🔨 Bezig, ✅ Gedaan, 🅿️ Geparkeerd
- Zoeken, filteren (status, categorie, favorieten) en sorteren
- Per idee een lijstje met volgende stappen, met voortgangsbalk
- 🎲 Verras me: kiest willekeurig een idee om op te pakken
- Ideeën delen of kopiëren
- Back-up downloaden en terugzetten (.json)

## Online zetten met GitHub Pages

1. Maak op github.com een nieuwe **openbare** repo, bijvoorbeeld `ideeen-vault`.
2. Klik op **Add file → Upload files** en sleep alle bestanden uit deze map erin (ook `.nojekyll`). Klik op **Commit changes**.
3. Ga naar **Settings → Pages**. Kies bij *Branch* `main` en `/ (root)` en klik op **Save**.
4. Na een minuut staat de app op `https://<gebruikersnaam>.github.io/ideeen-vault/`.

## Op je iPhone zetten

Open de link in **Safari**, tik op de deelknop en kies **Zet op beginscherm**. De app opent dan schermvullend met een eigen icoon.

## Waar worden mijn ideeën bewaard?

Alleen op je eigen apparaat, in de browser. Niets gaat naar GitHub of een server. Maak daarom af en toe een back-up via ⚙️, vooral voordat je van telefoon wisselt of je browsergegevens wist.

## Bestanden

| Bestand | Wat |
|---|---|
| `index.html` | De hele app |
| `manifest.webmanifest` | Naam en icoon voor het beginscherm |
| `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` | App-iconen |
| `.nojekyll` | Laat GitHub Pages de bestanden ongewijzigd serveren |
