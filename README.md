# Ordnerstrukturvorlage für die transparente Dokumentation einer quantitativen Studie.

Folgende Dateien sollen für eine transparente Dokumentation digital zugänglich gemacht werden:

```bash
├── 00_Studientext (z.B. Thesis)
│   ├── Text der Studie als .pdf
│   └── Text der Studie als .docx*
│
├── 01_Präregistrierung
│   └── Exposé und/oder Präregistrierung als .pdf mit Stand vor der Erhebung
│
├── 02_Material
│   ├── 02_01_Einladungstexte
│   │   └── verwendete Aushänge, Mails, Social Media Posts usw. als .pdf
│   ├── 02_02_Durchführungstexte (die nicht in anderen Dateien enthalten sind)
│   │   ├── Standardisierte Begrüßung als .pdf
│   │   ├── Standardisierte Instruktion als .pdf
│   │   ├── Vorlage Einverständnis- und Datenschutzerklärung als .pdf
│   │   ├── Standardisierte Probandeninformation als .pdf
│   │   └── Coverstory als .pdf
│   ├── 02_03_Fragebogen
│   │   ├── Printversion als .pdf
│   │   ├── Projektdatei je nach Tool, z.B. Unipark: .gpx, SoSci: .xml
│   │   └── Code für Ablaufsteuerung, z.B. JavaScript oder PHP
│   ├── 02_04_Stimuli
│   │   ├── Bilder, Videos im Originalformat
│   │   └── Dokumentation, Produktbilder, Handbücher zu verwendeten physischen Stimuli
│   └── 02_05_Experiment**
│       ├── Konfigurationsdatei je nach Tool, z.B. Tobii Pro Lab oder PsychoPy
│       ├── Dokumentation der Toolkonfiguration als .pdf
│       ├── Versuchsmanual
│       └── 02_05_01_Prätest
│           ├── Material
│           ├── Daten
│           └── Auswertung
│
├── 03_Daten
│   ├── Code-Buch z.B. als .xlsx
│   ├── 03_01_Rohdaten
│   │   ├── unveränderter Datensatz (belabelt) als .sav, .omv u.ä.
│   │   └── unveränderter Datensatz (reine Daten) als .csv
│   ├── 03_02_Datenaufbereitung
│   │   ├── Detaillierte Beschreibung der Behandlung fehlender Werte, Datenaggregation und Vpn-Ausschluß als .pdf inkl. Code-Syntax
│   │   └── Probanden Flow-Chart
│   └── 03_03_Aufbereitete_Daten
│       ├── finaler Datensatz (belabelt) als .sav, .omv u.ä.
│       └── finaler Datensatz (reine Daten) als .csv
│
├── 04_Auswertung
│   ├── 04_01_Code-Syntax
│   │   ├── basierend auf verwendeter Analysesoftware, z.B.: R: R Script, SPSS: .sps, jamovi: .omt
│   ├── 04_02_Ergebnisse
│   │   ├── SPSS: .spv (mit aktivierter Syntax in der Ausgabe), jamovi: .omv
│   └── 04_03_Abbildungen
│       └── außerhalb von Auswertungssoftware erzeugte Abbildungen
│
├── 05_Literatur
│   └── Exportierte Zotero-Sammlung OHNE Dateien der heruntergeladenen Literatur, z.B. als BibTex oder Zotero RDF
│
└── 06_KI-Nutzung***
    ├── Stellungnahme zur Nutzung von KI als .pdf
    └── Gesammelte Prompts und zugehörige Ausgaben als .pdf

*  : Oder anderes während des Schreibens verwendetes Format, z.B.: .odt, .tex, …
** : Falls keine experimentelle Studie durchgeführt wurde, diesen Ordner bitte entfernen.
***: Entfällt bei Nichtnutzung.
```
