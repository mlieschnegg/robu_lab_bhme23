# Laborprotokoll – 2026-09-23

> Vollständig erfundenes Unterrichtsbeispiel. Maße, Namen und Ergebnisse sind
> keine Angaben zum vorhandenen SCARA. In echten Protokollen Belege verlinken.

| Feld | Angabe |
|---|---|
| Klasse / Laborgruppe / Zweierteam | 4A / G1 / T2 |
| Mitglieder | Alex Beispiel, Kim Muster |
| Davon anwesend | beide |
| Roboter-ID | SCARA-4A-01 |
| Arbeitspaket / Meilenstein | Erstes Armgelenk untersuchen / M2 und M3 |

## Ziel

Gelenkachse und Abstand zur nächsten Achse für das URDF-Team bestimmen.
Prüfung: CAD-Maß mit dem montierten Arm vergleichen.

## Arbeiten und persönliche Beiträge

- Alex: Arm probeweise montiert und Achsabstand am Aufbau gemessen.
- Kim: Achsabstand aus dem übernommenen CAD abgelesen und Messwerte verglichen.
- Gemeinsam: Gelenkachse auf einer Skizze markiert und an das URDF-Team übergeben.
- Übernommen: Armkonstruktion der früheren Klasse; keine Geometrie selbst erstellt.

## Ergebnis und Prüfung

- Erstellt: Skizze mit Achslage und Vergleichstabelle.
- Durchführung: Achsabstand am CAD und dreimal am probeweise montierten Arm bestimmt.
- Erwartung: Abweichung höchstens 1 mm; zuvor für diesen Versuch vereinbart.

| CAD | Messung 1 | Messung 2 | Messung 3 |
|---|---|---|---|
| 150,0 mm | 150,4 mm | 150,3 mm | 150,5 mm |

- Ergebnis: Alle Messungen innerhalb der vereinbarten Toleranz.
- URDF-Übergabe: Achsabstand 0,150 m; Achsrichtung muss das Modellteam anhand
  seines gewählten Koordinatensystems eintragen.
- Belege: Im echten Protokoll CAD-Datei und Foto der Messstellen verlinken.

## Problem und Erkenntnis

Die erste Messung bezog sich auf Außenkanten statt Achsmitten. Wir haben die
Messstellen neu festgelegt. Außenmaße dürfen nicht direkt als Gelenkabstand dienen.

## Übergabe und nächster Schritt

- [ ] T3: Abstand ins Modell eintragen und Gelenkbewegung in RViz prüfen.
- Roboterstatus aktualisiert: Im echten Versuch nach der Montage erforderlich.
- Einschränkung: Nur Probeaufbau; noch keine motorische Inbetriebnahme.
