---
name: tabellen
description: Bringt Tabellen aus EN und DE trotz unterschiedlicher Zellstruktur (verbundene Zellen, doppelte Tabellenköpfe, Verschiebungen) in ein gemeinsames Raster mit Zellkoordinaten. Anwenden, sobald eine Tabelle im Text vorkommt.
---

# Tabellen

Zweck: Tabellen in EN und DE vergleichbar machen.

1. Tabellentitel = eigene Zeile ("Table 3 – Title" | "Tabelle 3 – Titel").
2. Das logische Raster (Zeilen-/Spaltenzahl, Kopfzeile) kommt aus EN. DE wird auf dasselbe Raster abgebildet.
3. Jede Zelle = eigene Zeile, zeilenweise von links nach rechts, mit sprachneutraler Koordinate am Anfang: `[T3-R2-C1] Inhalt`. Die Koordinate steht in BEIDEN Spalten identisch.
4. Kopfzeile = R0 (je Zelle eine Zeile). Wiederholte Köpfe nach Seitenumbruch ignorieren.
5. Verbundene Zellen: Inhalt nur bei der ersten (oberen/linken) Zelle, die übrigen als `[T3-R4-C2] (verbunden mit R3)` in BEIDEN Spalten. Ist in DE verbunden, in EN nicht (oder umgekehrt): Inhalt in die Zellen setzen, in die er laut EN-Raster gehört, und im Prüfbericht vermerken.
6. Mehrere Sätze in einer Zelle: je Satz eine Zeile, Koordinate nur in der ersten.
7. Leere Zellen: Zeile mit Koordinate und "–" nur, wenn die Zelle in EN existiert; sonst keine Zeile.
8. Tabellenfußnoten ("a", "b") und Quellenzeilen: eigene Zeilen nach der Tabelle.
