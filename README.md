# Agri-PV Visualizer

Konzept-Demo: Tracker-Agri-PV-Anlagen schematisch auf beliebige Luftbilder projizieren.

**Funktionen**

- Luftbild hochladen (bleibt lokal im Browser, kein Upload auf Server)
- Feldfläche über 4 verschiebbare Eckpunkte markieren (perspektivische Projektion per Homographie)
- Anlage konfigurieren: Reihenabstand, Modulbreite, Ausrichtung, Tageszeit (Tracker-Nachführung inkl. Schattenwurf)
- Kennzahlen-Schätzung: Fläche, Leistung (MWp), Pacht-Indikativ
- Export als PNG

**Nutzung**

Direkt im Browser öffnen, kein Build-Schritt nötig. Live-Version über GitHub Pages.

Rein statisch (HTML/CSS/JS in einer Datei), keine Abhängigkeiten, keine Datenübertragung.
