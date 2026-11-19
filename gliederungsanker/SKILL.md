---
name: gliederungsanker
description: Erstellt aus dem englischen Normtext ein Nummernskelett (Überschriften, Tabellen, Bilder, NOTE/EXAMPLE, Gleichungen) und ordnet damit die deutsche Fassung zu. Zu Beginn jedes Abschnitts anwenden, bevor segmentiert wird.
---

# Gliederungsanker

Zweck: Ein gemeinsames Gerüst aus EN erzeugen, an dem DE ausgerichtet wird.

## Vorgehen
1. Liste aus EN alle Überschriften mit Nummer in Dokumentreihenfolge ab "Scope" (1, 1.1, 1.1.1 ..., Annex A ...).
2. Liste alle Tabellen ("Table n"), Bilder ("Figure n"), NOTE-/EXAMPLE-Nummern und Gleichungsnummern.
3. Suche jeden Anker in DE (Tabelle n, Bild n / Abbildung n, ANMERKUNG n, BEISPIEL n, Gleichung (n)).
   - Überschriften über die Nummer finden. Fehlt die Nummer, über Position und Titelübersetzung.
4. Das Skelett ist die Wahrheit für Reihenfolge und Nummerierung. Weichen DE-Nummern ab, gilt die EN-Nummer.
5. Ankerliste intern führen. Nur bei Widersprüchen im Prüfbericht ausgeben.
