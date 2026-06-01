# MaRisk-Gap-Analyse Tool
Automatisierte MaRisk-Gap-Analyse: Das Tool extrahiert regulatorische Texte aus BaFin-PDFs, gleicht sie mit Bestandsfassungen ab und visualisiert Änderungen per Diff-Anzeige. Inkl. Dashboard zur Zuweisung von Status, Teams und Prioritäten sowie CSV-Export für Maßnahmenpläne. Ideal für Compliance & Audit.

## Funktionen
* **Automatisches Parsing:** PDF-Extraktion oder Web-Scraping der MaRisk.
* **Diff-Analyse:** Visueller Vergleich zwischen Alt- und Neu-Fassung.
* **Interaktives Dashboard:** Tracking von Status, Zuständigkeit & Priorität.
* **Daten-Export:** Speichern als JSON-Stand oder CSV-Maßnahmenplan.

## Benutzung
1. **Notebook starten:** Führe das Skript in Google Colab aus.
2. **Daten laden:** Masterdatei (Excel) und neue Fassung (PDF/URL) importieren.
3. **Analysieren:** Die Generierung erfolgt automatisch.
4. **Bearbeiten:** Öffne die `MaRisk_Differenzprotokoll.html` in deinem Browser.
5. **Speichern:** Fortschritt als JSON lokal sichern.

## Lizenz
Dieses Projekt ist unter der **MIT-Lizenz** lizenziert.

## Disclaimer
Das Tool dient als Unterstützung. Da es sich um eine automatisierte Textverarbeitung handelt, ist ein finaler Abgleich mit den Originaldokumenten der BaFin zwingend erforderlich.
