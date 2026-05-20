# Vox Helvetica Labs – Statische Beispiel-Website

**Eine statische Demo-Website als Beispiel für das vox helvetica lab**  

---

## 📌 Über das Projekt

Diese Website dient als **Beispielprojekt für Vox Helvetica Labs** und zeigt, wie statische Webseiten mit **HTML, CSS, JavaScript und SVG** umgesetzt werden können. Sie enthält:

- **Interaktive Karten** der Schweiz (basierend auf SVG und GeoJSON-Daten).
- **Datenvisualisierungen** (z. B. Pfade, Gemeinden, oder andere geographische Daten).
- **Responsive Design** für verschiedene Bildschirmgrößen.
- **Modulare Struktur** für einfache Erweiterungen.

Die Website ist **vollständig statisch** und kann auf jedem Hosting-Dienst für statische Inhalte deployt werden (z. B. GitHub Pages, Netlify, Vercel).

---

## 🚀 Live-Demo

🔗 **[Zur Live-Demo](https://lucakeiser.github.io/Uni_Basel/)**

*(Hinweis: URL anpassen, falls du eine benutzerdefinierte Domain verwendest.)*

---

## 📁 Projektstruktur

```
Uni_Basel/
├── index.html          # Hauptseite der Website
├── swiss_svg_inner.html # SVG-basierte Karte der Schweiz
├── gemeinden_svg.html  # SVG-Darstellung der Schweizer Gemeinden
├── swiss_paths.json    # GeoJSON-Daten für Pfade/Karten
├── methodik.html       # Dokumentation der Methodik
├── chat.html           # Beispielseite für interaktive Elemente
├── assets/             # (Optional) Bilder, Stylesheets, Skripte
│   ├── css/
│   │   └── style.css   # Haupt-Stylesheet
│   └── js/
│       └── main.js     # Haupt-JavaScript-Datei
└── README.md           # Diese Datei
```

---

## 🛠 Technologien


| Technologie    | Verwendung                                     |
| -------------- | ---------------------------------------------- |
| **HTML5**      | Struktur der Webseiten                         |
| **CSS3**       | Styling und Layout                             |
| **JavaScript** | Interaktivität (z. B. Kartensteuerung)         |
| **SVG**        | Vektorbasierte Kartendarstellungen             |
| **GeoJSON**    | Geographische Daten (z. B. `swiss_paths.json`) |


---

## 📥 Installation & Lokale Nutzung

### 1. Repository klonen

```bash
git clone https://github.com/LucaKeiser/Uni_Basel.git
cd Uni_Basel
```

### 2. Lokale Vorschau

Öffne die `index.html` direkt in deinem Browser oder nutze einen lokalen Server (z. B. mit Python):

```bash
# Python 3
python3 -m http.server 8000
```

→ Die Website ist dann unter [http://localhost:8000](http://localhost:8000) erreichbar.

---

## 🌍 Deployen

### Option 1: GitHub Pages (empfohlen)

1. Lade alle Dateien in dein GitHub-Repository hoch.
2. Gehe zu **Settings → Pages** und wähle:
  - **Branch:** `main`
  - **Folder:** `/root` (oder `/docs`, falls die Dateien dort liegen).
3. Die Website ist unter `https://<dein-benutzername>.github.io/Uni_Basel/` erreichbar.

### Option 2: Netlify/Vercel

- Ziehe die Projekt-Dateien per **Drag & Drop** auf [Netlify](https://www.netlify.com/) oder [Vercel](https://vercel.com/).
- Die Website wird automatisch deployt.

---

## 🔧 Anpassungen

### Daten aktualisieren

- **Kartendaten:** Ersetze die Datei `swiss_paths.json` mit neuen GeoJSON-Daten.
- **Stile anpassen:** Bearbeite die CSS-Dateien im `assets/css/` Ordner.

### Neue Seiten hinzufügen

1. Erstelle eine neue `.html`-Datei (z. B. `neue-seite.html`).
2. Verlinke sie in der `index.html` oder Navigation.

---

## 📜 Lizenz

Dieses Projekt ist **open source** und steht unter der [MIT-Lizenz](LICENSE).  
*(Falls gewünscht, kann eine `LICENSE`-Datei hinzugefügt werden.)*

---

## 🤝 Beitrag leisten

Beiträge sind willkommen! Falls du Fehler findest oder Verbesserungen vorschlagen möchtest:

1. Forke das Repository.
2. Erstelle einen neuen Branch (`git checkout -b feature/neue-funktion`).
3. Committe deine Änderungen (`git commit -m "Beschreibung der Änderung"`).
4. Push den Branch (`git push origin feature/neue-funktion`).
5. Erstelle einen **Pull Request**.

---

## 📧 Kontakt

Für Fragen oder Feedback:

- **E-Mail:** [luca.keiser@keisi.ch](mailto:luca.keiser@keisi.ch)
- **GitHub:** [@LucaKeiser](https://github.com/LucaKeiser)
- **Organisation:** [Keisi](https://github.com/Keisi)
