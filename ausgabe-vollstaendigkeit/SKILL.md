---
name: ausgabe-vollstaendigkeit
description: Legt das Ausgabeformat (Tabelle mit zwei Spalten EN/DE), den Prüfbericht und die Vollständigkeitskontrolle fest. Als letzten Schritt jedes Abschnitts anwenden und bei EXCEL für den Export.
---

# Ausgabe und Vollständigkeit

## Ausgabe
- Markdown-Tabelle mit Kopf `| EN | DE |`, je Segment-Paar eine Zeile, keine weiteren Spalten.
- Keine Zeilenumbrüche innerhalb einer Zelle. Pipe-Zeichen im Text als `\|` schreiben.
- Bei "EXCEL": .xlsx mit Spalte A = EN, Spalte B = DE, Zeile 1 = Überschriften, alle Zeilen unverändert.

## Prüfbericht (nach der Tabelle, max. 8 Zeilen)
- Abschnitt von … bis …
- Anzahl EN-Zeilen / DE-Zeilen mit Inhalt / Leerzellen
- Gefundene Überschriften EN vs. DE
- Tabellen: EN-Zellen vs. DE-Zellen je Tabelle
- Korrekturen aus der Nachbarschaftsprüfung (Anzahl, kurz)
- Markierte Unsicherheiten "[?]" mit Zeilennummer
- Ausgelassene DE-Zusatztexte (Kommentare, Kopfzeilen), nur kurz benannt

## Vollständigkeit
Vor "fertig" prüfen:
- Die letzte Zeile entspricht dem letzten Satz des EN- UND des DE-Abschnitts.
- Kein Anker aus dem Skill `gliederungsanker` fehlt.

Am Dokumentende ausdrücklich schreiben: "Dokument vollständig bis <letzte Überschrift>" oder die Lücke nennen.
