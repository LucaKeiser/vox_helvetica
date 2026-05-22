# Vox Helvetica Labs – Statische Beispiel-Website

**Eine statische Demo-Website als Beispiel für das vox helvetica lab-Projekt**  

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

🔗 **[Zur Live-Demo](https://lucakeiser.github.io/civitas_helvetica/)**

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
