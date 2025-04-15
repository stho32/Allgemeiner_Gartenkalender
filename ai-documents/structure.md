# Projektstruktur von Allgemeiner Gartenkalender

Dieses Dokument beschreibt die Verzeichnis- und Dateistruktur des Projekts **Allgemeiner Gartenkalender**.

## Übersicht

```
Allgemeiner_Gartenkalender/
├── .git/                 # Git-Versionskontrolle (verstecktes Verzeichnis)
├── README.md             # Projektbeschreibung und Hinweise
├── ai-documents/         # Ablage für AI-generierte Dokumente
├── beetvergabe.html      # HTML-Datei für Beetvergabe
├── index.html            # Hauptseite des Kalenders
├── monate/               # Monatsübersichten als HTML-Dateien
│   ├── august.html
│   ├── dezember.html
│   ├── februar.html
│   ├── januar.html
│   ├── juli.html
│   ├── juni.html
│   ├── maerz.html
│   ├── mai.html
│   ├── november.html
│   ├── oktober.html
│   └── september.html
└── styles.css            # Zentrales CSS-Stylesheet
```

## Details zu den wichtigsten Verzeichnissen und Dateien

- **.git/**: Enthält alle Informationen zur Versionsverwaltung mit Git. Wird automatisch von Git angelegt und verwaltet.
- **README.md**: Enthält eine Beschreibung des Projekts, Installationshinweise und ggf. weitere Informationen.
- **ai-documents/**: Hier werden AI-generierte Dokumente abgelegt, wie z.B. diese Strukturübersicht. Das Verzeichnis ist aktuell leer.
- **beetvergabe.html**: HTML-Seite zur Verwaltung oder Anzeige der Beetvergabe.
- **index.html**: Die Hauptstartseite des Gartenkalenders.
- **monate/**: Enthält für jeden Monat eine eigene HTML-Datei mit spezifischen Informationen und Aufgaben.
    - **januar.html** bis **dezember.html**: Jeweils eine Datei pro Monat, die die relevanten Gartenarbeiten oder Hinweise enthält.
- **styles.css**: Zentrales Stylesheet für das gesamte Projekt.

---

*Letzte Aktualisierung: 15.04.2025*
