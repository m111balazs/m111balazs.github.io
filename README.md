# Digital Marketing Plus (DMP)

## Mappa struktúra

├── my\_marketing\_app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── frontend/
│   │   │   │   ├── assets/              # Képek, ikonok, fontok
│   │   │   │   ├── components/         # Újrafelhasználható UI elemek (gombok, kártyák, stb.)
│   │   │   │   ├── pages/              # Oldalak (dashboard, kampánytervező, beállítások)
│   │   │   │   ├── services/           # Frontend-en futó logikai réteg (pl. API hívások kezelése)
│   │   │   │   ├── styles/             # CSS fájlok, UI tematikus stílusok
│   │   │   │   └── App.js              # Fő komponens
│   │   ├── backend/
│   │   │   ├── controllers/            # Kezeli a kéréseket és a válaszokat
│   │   │   ├── models/                 # Adatbázis sémák
│   │   │   ├── routes/                 # API végpontok definiálása
│   │   │   ├── services/               # Üzleti logika (adatbázis műveletek, számítások)
│   │   │   └── app.js                  # Szerver fő fájl
│   ├── database/
│   │   ├── migrations/                 # Adatbázis sémák változásainak követése
│   │   └── seeds/                      # Teszt adatok
│   ├── config/
│   │   ├── api\_keys.js                 # API kulcsok és titkos adatok
│   │   └── database.js                 # Adatbázis kapcsolódási adatok
│   └── package.json                    # Függőségek és scriptek

## Color palette

&nbsp;	--accent-color: #8672FF;

&nbsp;	--base-color: #FFF;

&nbsp;	--text-color: #2E2B41;

&nbsp;	--input-color: #F3F0FF;

&nbsp;	--accent-hover: #725BE6;

&nbsp;	--accent-light: #B4A9E6;

&nbsp;	--text-secondary: #5C5873;

&nbsp;	--text-placeholder: #B4B0C7;

&nbsp;	--border-color: #E0DAF0;

&nbsp;	--error-color: #f06461;

&nbsp;	--success-color: #76dd79;

