# ZitationSteinbeis
CSL-Stil für Steinbeis Hochschule
  Version: 1.0 | Erstellt: 2025-04-17 | Autor: sli

##  Stilbeschreibung:
  - Fußnoten im deutschen Stil mit „Vgl.“ und Initialen
    →  bei direktem Zitat „Vgl.“ entfernen!
  - Literaturverzeichnis nach APA (modifiziert nach Angaben in: Anforderungen an Abschlussarbeiten und sonstige wissenschaftliche Forschungsarbeiten für Studierende an der Steinbeis Hochschule Stand: 2024)


##  🔧 Hinweise ! WICHTTIG:
  - Funktioniert mit Zotero 6+ und Juris-M
  - ! Keine Ausgabe der 1. Auflage laut SBA
      → Edition-Feld muss leer bleiben!
  - Bei Webseiten Institutionen als Author nicht möglich in Zotero Einstellung
    → Fallback auf short-title für Instituionsnamen
  - Unterstützt folgende Typen:
    - book: Buch und Sammelband (Unterscheidung via if editor)
    - chapter: Einzelkapitel
    - article-journal:  Aufsatz in einer (wissenschaftlichen) Zeitschrift
    - article-newspaper: Zeitungen
    - webpage: Internetquellen
    - manuscript: Interne/unveröffentlichte Quellen
    - speech: Präsentation (da typ presentation in Zotero ungültig)

##  ⚠️ Im Literaturverzeichnis beachten
  - Bei Problemen bitte Quellentyp in Zotero prüfen und ggf. anpassen, oder cases erweitern
  - `if (URL)` Case: bei book, chapter, article-journal, article-newspaper verfügbar
        → falls URL nicht erwünscht:
            - jeweiligen `<choose>` Block entfernen oder,
            - Hinterlegte URL in Zotero entfernen und ggf. als Notiz ablegen falls weiter benötigt
