Versuchsanweisung

### Vergleich der lokalen Uhrenspuren von A, B und S

Projekt: Gegenhypothese „Lokale Struktur von Raum, Gravitation, Zeit und Materie" Autor: Destiny Rai-Ko Pulvermacher · ORCID 0009-0003-9431-1001 Stand: 2. Oktober 2026

Kern des Verfahrens: Es wird nichts gerechnet, nichts korrigiert, nichts eingesetzt. Es wird abgelesen, ob zwei Spuren aufeinanderfallen.

## Teil E – Versuchsanweisung

Protokoll zur Durchführung. Keine Deutung, keine Korrektur, keine Konstante im Verfahren.

### E.1 Zweck

Feststellen, ob die beiden Spuren sich decken oder nicht.

### E.2 Messsysteme

| Kennung | System | Aufgabe |
| --- | --- | --- |
| A | Flugzeug, westwärts | lokal messen, aufzeichnen, Marker quittieren |
| B | Flugzeug, ostwärts | lokal messen, aufzeichnen, Marker quittieren |
| S | Bodenstation | lokal messen, aufzeichnen, Marker quittieren |
| C | Auswertestelle | Spuren überlagern, Versatz ablesen |

C misst nicht. C legt zusammen.

### E.3 Messkette

Lokales Ereignis → lokale Uhr → lokale Frequenzmessung → Speicherung → Übertragung.

Jeder Datensatz führt seinen eigenen Zeitstempel mit. Übertragen wird der gespeicherte Wert, nicht die Frequenz als Messvorgang.

### E.4 Marker-Protokoll

Doppelmarker-Prinzip. Jeder Marker wird von zwei Systemen gesetzt und von beiden quittiert.

| Schritt | Vorgang |
| --- | --- |
| 1 | System X setzt Marker M_n und speichert: Marker-ID + eigene lokale Zeit + eigene Messdaten |
| 2 | System X sendet an System Y: „M_n gesetzt" |
| 3 | System Y setzt denselben Marker M_n in seiner eigenen Aufzeichnung und speichert dieselbe Struktur |
| 4 | System Y quittiert an X: „M_n okay" |
| 5 | X speichert die Quittung |

Ergebnis: Derselbe Marker liegt in beiden Aufzeichnungen – mit je eigener lokaler Zeit. Das ist der Bezug, über den später überlagert wird.

Die Quittung ist Kennzeichnung, keine Zeitmessung. Die Laufzeit der Quittung spielt für das Ergebnis keine Rolle.

#### Marker-Katalog

| ID | Ereignis |
| --- | --- |
| M00 | Start der Messung |
| M01 | Abheben |
| M02 | Messhöhe erreicht (10 000 m) |
| M03 | Konstantflug beginnt |
| M04 | Geschwindigkeitszustand 1 (A = B) |
| M05 | Geschwindigkeitszustand 2 (A langsamer) |
| M06 | Geschwindigkeitszustand 3 (A schneller) |
| M07 | Konstantflug endet |
| M08 | Wende |
| M09 | Rückflug beginnt |
| M10 | Landung |
| M90 | Ende der Messung |

Jeder Marker enthält: Kennung + lokale Uhrzeit + Höhe + Geschwindigkeit + lokale Frequenz + Quittungsstatus.

### E.5 Flugprofil

| Größe | Vorgabe |
| --- | --- |
| Höhe | 10 000 m, Toleranz ±100 m, ausdrücklich konstant gehalten |
| Korridorlänge | 6 000–8 000 km, definierter Umkehrpunkt |
| Geschwindigkeitszustände | 250 m/s (gleich) / A 220 m/s / A 280 m/s |
| Dauer je Zustand | ≥ 4 h |
| Richtung | A westwärts, B ostwärts, beide gleichzeitig |
| Rückweg | Wende, Rückflug zum Ausgangspunkt |

### E.6 Datenformat

| System | Marker | lokale Uhrzeit | Höhe [m] | Geschwindigkeit [m/s] | lokale Frequenz [Hz] | Quittung von |
| --- | --- | --- | --- | --- | --- | --- |
| A | M03 |  |  |  |  | B, S |
| B | M03 |  |  |  |  | A, S |
| S | M03 |  |  |  |  | A, B |

Fortlaufende Aufzeichnung zwischen den Markern, nicht nur die Markerpunkte.

### E.7 Auswertung – sechs Schritte

1. Rohdaten aller Systeme übernehmen. Unverändert. Keine Korrektur.

1. Nach mitgeführter lokaler Uhr sortieren. Nicht nach Ankunftszeit.

1. Spuren über die Marker aufeinanderlegen. A rot, B blau.

1. Ablesen: Deckung oder Versatz?

1. Versatz je Markerabschnitt in ns eintragen.

1. Tabelle ausfüllen.

Es wird nichts gerechnet. Es wird nichts korrigiert. Es wird abgelesen.

### E.8 Ausfülltabelle

| Markerabschnitt | Dauer A [ns] | Dauer B [ns] | Differenz [ns] | Deckung ja/nein |
| --- | --- | --- | --- | --- |
| M03 → M04 |  |  |  |  |
| M04 → M05 |  |  |  |  |
| M05 → M06 |  |  |  |  |
| M06 → M07 |  |  |  |  |
| M03 → M07 gesamt |  |  |  |  |

### E.9 Fehlerbudget

| Quelle | Größe | Behandlung |
| --- | --- | --- |
| Uhrenstabilität (Gitteruhr) | ~10⁻⁴ ns über 13 h | vernachlässigbar |
| Uhrenstabilität (Cs-Beam) | ~1 ns über 13 h | dokumentieren |
| Marker-Auslöseverzögerung | 10–100 ns, systematisch | kalibrieren, in beiden Systemen gleich |
| Höhenmessung | 1 m entspricht 1,1 × 10⁻¹⁶ | GNSS + Barometrie, protokollieren |
| Temperatur / Magnetfeld / Vibration | gerätespezifisch | nach Herstellerangabe |

### E.10 Vergleichswert – keine Korrektur

Nach dem Ausfüllen der Tabelle wird danebengelegt, was eine Rechnung mit Berücksichtigung der Erdrotation ergibt: rund 121 ns nach 13 h.

Dieser Wert wird nicht in die Auswertung eingesetzt. Er dient nur dem Vergleich. Die Auswertung selbst kommt ohne ihn aus.

### E.11 Ergebnis

| Befund nach Schritt 4 | Aussage |
| --- | --- |
| Deckung innerhalb des Fehlerbudgets | Gleiche Höhe, gleiche Geschwindigkeit, Gegenrichtung → keine Wirkung der Geschwindigkeit. Die Ausgangserwartung des Aufbaus steht. |
| Kein Deckung | Bei identischer Höhe und identischem Geschwindigkeitsbetrag tritt ein Unterschied auf. Der Betrag ist dem Protokoll zu entnehmen; eine Ursache ist nicht Teil dieses Protokolls. |

Beide Befunde sind Ergebnisse. Keiner davon verlangt, dass vorher eine Zahl eingesetzt wird.

### E.12 Was dieses Protokoll nicht tut

- Es rechnet nichts um.

- Es korrigiert nichts.

- Es setzt keine Konstante ein.

- Es deutet nichts.

- Es liest ab, ob zwei Spuren aufeinanderfallen.