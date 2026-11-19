---
name: nachbarschaftspruefung
description: Prüft jede Zeile der EN/DE-Tabelle durch Vergleich mit den 10 Zeilen davor und danach, um falsch getrennte, verschobene oder vergessene Paare zu finden und zu korrigieren. Nach der Paarung anwenden. Keine vollständige Übersetzungsprüfung.
---

# Nachbarschaftsprüfung (±10 Zeilen)

Für jede Zeile n:

1. **Plausibilität:** Passen Zahlen, Einheiten, Fachbegriffe, Satzart und Länge von EN und DE? Wenn ja: OK.
2. **Wenn nein:** durchsuche die DE-Zellen der Zeilen n-10 bis n+10 nach der inhaltlich passenden DE-Zeile.
3. **Fall A, Verschiebung:** Die passende DE-Zeile liegt woanders. Zuordnung korrigieren und alle Zeilen dazwischen neu paaren.
4. **Fall B, falsch zusammengefasst:** Eine DE-Zelle enthält zwei Sätze, die zu zwei EN-Zeilen gehören. DE-Zelle trennen.
5. **Fall C, falsch getrennt:** Ein DE-Satz steht auf zwei Zeilen, EN auf einer. Verbinden.
6. **Fall D, nichts gefunden:** Zelle leer lassen und im Prüfbericht melden.
7. **Zusatzprüfungen:**
   - Stimmt die Nummerierung beider Spalten pro Zeile überein?
   - Stimmen Anzahl der Listenpunkte und Tabellenzellen je Tabelle in EN und DE?
8. Wiederhole die Prüfung nach jeder Korrektur, bis keine Auffälligkeit mehr besteht (max. 3 Durchläufe).
