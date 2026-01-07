# Lernlandschaft – Fanny Lewald: Jenny

## Struktur
- `index.html` – komplette Lernlandschaft (PDFs, Bilder, Musik, 50 Fragen mit Sofortkorrektur)
- `assets/pdf/` – PDFs (Roman + Biografie)
- `assets/audio/` – Musik (charakterstuecke.mp3)
- `assets/images/` – alle Bildressourcen

## GitHub Pages
1. Repository erstellen und diese Dateien hochladen (Ordnerstruktur beibehalten).
2. GitHub → Settings → Pages → Deploy from branch → Branch: `main` / root.
3. Seite öffnen: PDFs laufen als eingebettete iframes; falls ein Browser das blockt: Links „in neuem Tab öffnen“ nutzen.

## Reset / Speicherung
- Quiz speichert Fortschritt im Browser (`localStorage`).
- Reset-Button löscht alle Eingaben/Versuche.

