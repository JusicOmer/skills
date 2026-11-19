---
name: dt-bereinigung
description: Behebt Konvertierungsfehler im deutschen Text (aus PDF nach Word): falsche Absätze, Zeilenumbrüche, Silbentrennung, zerrissene oder falsch formatierte Nummern, Kopf-/Fußzeilen, Übersetzerkommentare. Vor der Segmentierung der deutschen Fassung anwenden.
---

# Bereinigung der DE-Konvertierung

Zweck: Konvertierungsfehler beheben, ohne den Inhalt zu ändern.

## Entfernen
- Kopf-/Fußzeilen, Seitenzahlen, Dokumentcodes als Seitenkopf, Wasserzeichen
- Übersetzer-/Redaktionshinweise ("Anmerkung des Übersetzers", nationale Anmerkungen, nationales Vorwort)
- mehrfach auftretende Tabellenköpfe nach Seitenwechsel
- Sonderzeichen-Müll, Zwischenbuchstaben

## Reparieren
- Harte Zeilenumbrüche mitten im Satz: zu einem Satz verbinden.
- Silbentrennung am Zeilenende ("Anwen-\ndung"): Wort zusammenfügen.
- Falsche Absätze/Einrückungen: ignorieren, nur Satzgrenzen zählen.
- Überschrift auf zwei Zeilen/Absätze verteilt (Nummer oben, Titel unten oder umgekehrt): zu "Nummer Titel" zusammenführen.
- Fehlende Nummer an Überschrift oder Liste: aus dem EN-Gegenstück ergänzen (Skill `gliederungsanker`).
- Falsch formatierte Nummern ("1 . 1", "1.1Historie", "1,1 Historie"): normalisieren zu "1.1 Historie".

## Nicht ändern
Fachbegriffe, Zahlenwerte, Einheiten, Rechtschreibung des Inhalts. Bei Unsicherheit Text unverändert lassen und "[?]" anhängen.
