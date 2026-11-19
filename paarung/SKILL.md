---
name: paarung
description: Ordnet jede englische Zeile genau einer deutschen Zeile zu (Alignment) anhand von Nummern, Zahlen, Einheiten, Satzart und Reihenfolge. Anwenden, nachdem EN und DE segmentiert wurden.
---

# Paarung (Alignment)

Zweck: Jede EN-Zeile mit ihrer DE-Zeile verbinden.

1. Gehe die EN-Zeilen der Reihe nach durch. Suche für jede die nächste noch unbenutzte DE-Zeile in Reihenfolge.
2. Prüfe die Passung in dieser Priorität:
   a) gleiche Nummer/Marker/Koordinate
   b) gleiche Zahlen, Einheiten, Formelzeichen, Eigennamen, Normverweise
   c) ähnliche Satzlänge und Satzart
   d) Reihenfolge
3. Eine EN-Zeile gehört zu genau EINER DE-Zeile und umgekehrt (1:1).
4. Passt ein DE-Satz nicht zu genau einer EN-Zeile:
   - DE hat zwei Sätze, EN einen (oder umgekehrt): prüfe, ob die Trennung gegen die Regeln des Skills `segmentierung` verstößt, und korrigiere sie nach der EN-Segmentierung.
   - Kein DE-Gegenstück: DE-Zelle leer.
   - Kein EN-Gegenstück (zusätzlicher DE-Text, der kein Übersetzer-/Redaktionshinweis ist): EN-Zelle leer.
5. Nie raten. Bei unsicherer Zuordnung "[?]" an die DE-Zelle hängen und im Prüfbericht nennen.
6. Die Zeilenreihenfolge folgt EN. Zeilen nie verschieben, nur um Lücken zu füllen.
