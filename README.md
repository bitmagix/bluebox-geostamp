# 📍 CGH - Claude's Geo Hack

Geo-Timestamp Kamera PWA (Progressive Web App)

## Features

✅ **Kamera-Zugriff** - Nutzt die Handy-Kamera  
✅ **GPS-Tracking** - Erfasst exakte Position beim Auslösen  
✅ **Live-Overlay** - Zeigt Preview von Timestamp + Koordinaten  
✅ **Foto-Download** - Brennt alle Infos dauerhaft ins Bild  
✅ **Kamera wechseln** - Front/Rück-Kamera umschalten  
✅ **PWA-Ready** - Als App auf dem Handy installierbar  

## Schnellstart (Lokal testen)

1. Öffne `index.html` direkt im Browser (Chrome/Edge/Firefox)
2. Erlaube Kamera + GPS-Zugriff
3. Fertig! 📸

**WICHTIG:** Für GPS/Kamera braucht die App HTTPS oder localhost!

## Hosting Optionen (in 2 Minuten live!)

### Option 1: **GitHub Pages** (Empfohlen - Gratis)
```bash
# 1. Git Repo erstellen
git init
git add .
git commit -m "Initial commit"

# 2. Auf GitHub pushen (erstelle vorher ein Repo auf github.com)
git remote add origin https://github.com/DEIN-USERNAME/cgh.git
git push -u origin main

# 3. In GitHub Repo Settings > Pages:
#    - Source: "main" branch
#    - Folder: "/ (root)"
#    - Save

# Live in 1-2 Minuten unter: https://DEIN-USERNAME.github.io/cgh
```

### Option 2: **Vercel** (Noch schneller)
```bash
# 1. Vercel CLI installieren
npm install -g vercel

# 2. Im Projekt-Ordner:
cd C:\Projekte\CGH
vercel

# 3. Folge den Prompts (dauert 30 Sekunden)
# Live URL kriegst du sofort!
```

### Option 3: **Netlify Drop**
1. Gehe zu https://app.netlify.com/drop
2. Ziehe den ganzen `CGH` Ordner ins Fenster
3. FERTIG! URL bekommst du sofort

## Als App installieren (Handy)

**Android/Chrome:**
1. Öffne die gehostete URL im Chrome Browser
2. Menü (⋮) > "Zum Startbildschirm hinzufügen"
3. App ist jetzt wie eine native App verwendbar!

**iOS/Safari:**
1. Öffne die gehostete URL in Safari
2. Teilen-Button > "Zum Home-Bildschirm"
3. Fertig!

## Troubleshooting

**"Kamera funktioniert nicht"**
- App muss über HTTPS laufen (oder localhost)
- Browserberechtigungen prüfen

**"GPS funktioniert nicht"**
- GPS auf dem Handy aktiviert?
- Browser-Standortberechtigung erteilt?
- Evtl. draußen testen (besserer GPS-Empfang)

**"Bild wird nicht gespeichert"**
- Download-Berechtigung im Browser erteilen

## Technische Details

- **Keine Dependencies** - Reines HTML/CSS/JavaScript
- **Funktioniert offline** - Nach erstem Laden (dank Service Worker)
- **Cross-Platform** - Android, iOS, Desktop
- **Kein App Store nötig** - Läuft direkt im Browser

## Nächste Schritte (falls gewünscht)

- [ ] Formatierung anpassbar machen (Schriftgröße, Position, Farbe)
- [ ] Mehrere Fotos in Session speichern
- [ ] Export-Optionen (WhatsApp, Email)
- [ ] Dark/Light Mode
- [ ] Compass/Höhe hinzufügen

---

**Made with ⚡ by Claude & Cel**