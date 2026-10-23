# Anhang 04 – Flugzeugplattform und Messstabilisierung

**Projekt:** Lokale Struktur von Raum, Gravitation, Zeit und Materie  
**Autorin:** Destiny Rai-Ko Pulvermacher · ORCID: 0009-0003-9431-1001  
**Dokumenttyp:** Technisches Konzept / vorläufige Versuchsauslegung  
**Status:** Entwurf; technische Eignung und Messunsicherheiten noch zu validieren  
**Bezug:** `Gegenhypothese_Konzept.md` und `Versuchsanweisung.md`

## 1. Ziel und Abgrenzung

Dieser Anhang konkretisiert die technische Ausrüstung zweier baugleicher Forschungsflugzeuge für die Untersuchung von Beziehungen zwischen Gravitation, Bewegung und lokal gemessener Zeit beziehungsweise Frequenz. Er beschreibt die Infrastruktur und deren Störgrößenkontrolle; er behauptet weder die technische Machbarkeit einer bestimmten Genauigkeit noch ein experimentelles Ergebnis.

Die Wahl der Atomuhren, Laser, optischen Referenzen und Zeitübertragungsverfahren bleibt ausdrücklich **offen**. Ihre Spezifikation erfolgt erst nach Festlegung der zu unterscheidenden Vorhersagen und eines vollständigen Messunsicherheitsbudgets.

## 2. Flugzeugplattform

Als **vorläufiger Referenzkandidat** werden zwei Airbus A350-900 betrachtet. Die endgültige Auswahl erfordert einen Vergleich mit alternativen Flugzeugplattformen hinsichtlich Nutzlast, Flugprofil, struktureller Schwingungen, elektrischer Versorgung, Umbaufähigkeit, Zulassung und Kosten.

Die Flugzeuge sollen nach Möglichkeit dieselbe Muster- und Ausrüstungsvariante besitzen. Gleichheit des Flugzeugtyps allein gewährleistet keine identischen Messbedingungen. Deshalb sind tatsächliche Masse, Schwerpunkt, Treibstoffverteilung, Triebwerkszustand, Flugregelung und mechanische Eigenfrequenzen für jedes Flugzeug gesondert zu erfassen.

Die größeren Abmessungen und die Massenträgheit eines Großraumflugzeugs können bei bestimmten Turbulenzanregungen günstig sein; eine pauschal geringere Schwingungsbelastung ist daraus nicht ableitbar.

## 3. Umrüstung zu fliegenden Laboren

Vorgesehen sind getrennte Bereiche für:
- Präzisionszeit- und Frequenzmesstechnik;
- mechanisch entkoppelte optische Aufbauten;
- Stromversorgung, Notstromversorgung und Überwachung;
- Datenaufzeichnung und Kommunikation;
- wissenschaftliches und flugbetriebliches Personal.

Die Einbauorte sollen unter Berücksichtigung von Schwerpunktnähe, struktureller Steifigkeit, Zugänglichkeit und lokalen Schwingungsspektren bestimmt werden. Die Integration muss luftrechtlich geprüft und zugelassen werden; sicherheitsrelevante Flugzeugsysteme bleiben von den wissenschaftlichen Messsystemen funktional getrennt.

## 4. Bewegungserfassung und Schwingungsisolierung

### 4.1 Gyroskope und inertiale Messeinheiten

Hochwertige dreiachsige Gyroskope, beispielsweise Ringlaser- oder faseroptische Gyroskope, erfassen Winkelgeschwindigkeiten. Dreiachsige Beschleunigungssensoren messen spezifische Beschleunigungen. Kombinierte inertiale Messeinheiten (IMU) unterstützen die Rekonstruktion des Bewegungszustands und die Zuordnung von Störereignissen.

**Wichtig:** Ein Gyroskop stabilisiert eine optische Plattform nicht von selbst. Es liefert Messgrößen für die Überwachung oder eine geeignete Regelung.

### 4.2 Mechanische Isolation

Für empfindliche Instrumente sind passive und gegebenenfalls aktive Schwingungsisolatoren vorgesehen. Deren Eignung muss für das tatsächliche Schwingungsspektrum im Flug, die zu tragende Masse und die geforderte Ausrichtung untersucht werden. Eine Isolierung kann einzelne Frequenzbereiche verbessern und andere verschlechtern; daher sind Messungen am Einbauort erforderlich.

### 4.3 Referenzsensorik

Zusätzliche Sensoren an Instrumententischen, Befestigungspunkten und Flugzeugstruktur dokumentieren mögliche Kopplungen zwischen Flugzustand, Vibrationen und Messwerten. Rohsignale und Kalibrierungen bleiben erhalten.

## 5. Umwelt- und Versorgungskontrolle

Für die Präzisionsinstrumente werden unabhängig überwachte und, soweit erforderlich, geregelte Gehäuse oder Laborzonen vorgesehen. Relevante Größen sind:
- Temperatur, räumliche Temperaturgradienten und zeitliche Schwankungen;
- Druck und Feuchte;
- Magnetfelder und elektromagnetische Störungen;
- mechanische Beschleunigungen;
- Versorgungsspannung, elektrische Störungen und Ausfälle.

Die konkreten Grenzwerte werden **nicht vorab erfunden**, sondern aus den späteren Gerätespezifikationen und der Unsicherheitsanalyse abgeleitet. Die Druckregelung der Flugzeugkabine bleibt innerhalb der zulässigen Betriebsgrenzen. Bei optischen Komponenten können evakuierte oder thermisch besonders stabilisierte Einhausungen erforderlich sein.

## 6. Atomuhren und Lasersysteme: Technologie offen

Die endgültige Auswahl bleibt einer separaten Technologie- und Machbarkeitsstudie vorbehalten. Zu vergleichen sind insbesondere:
- erreichbare Frequenzstabilität und systematische Unsicherheit;
- Robustheit gegenüber Flugvibrationen, Beschleunigungen und Temperaturänderungen;
- notwendige optische Referenzen, Frequenzkämme und Vergleichsverfahren;
- Dauerbetrieb, Wartbarkeit, Energiebedarf und Masse;
- Kalibrierbarkeit vor, während und nach den Flügen.

**Femtosekunden-Zeitauflösung, Frequenzstabilität und absolute Messunsicherheit sind unterschiedliche Eigenschaften.** Die Eignung eines Systems lässt sich nicht allein aus einer angegebenen fraktionalen Frequenzunsicherheit ableiten.

## 7. Navigation, Zeitmarken und Datenkette

Die Messkette bleibt gemäß Projektkonzept: **lokal messen → lokal zeitstempeln → unverändert speichern → übertragen → zusammenführen → auswerten**.

Aufzuzeichnen sind lokale Uhren- und Frequenzdaten, Marker-IDs, Navigationsdaten, Flughöhe, Geschwindigkeiten mit explizit benanntem Bezugssystem, Lage- und Beschleunigungsdaten sowie Umwelt- und Betriebszustände.

Die Bodenstation C dient der Zusammenführung der Datensätze; sie muss dafür nicht als zusätzliche physikalische Uhr des ursprünglichen Experiments definiert werden. **Ein gemeinsamer Markername oder eine Funkquittung beweist jedoch keine Gleichzeitigkeit räumlich getrennter Ereignisse.** Sollen Zeitdifferenzen zwischen entfernten Systemen quantitativ bestimmt werden, müssen Zeitübertragung, Laufzeiten, Zeitstempelbildung und Synchronisationsunsicherheiten gesondert charakterisiert werden. Die Rohdaten bleiben dabei unverändert; abgeleitete und gegebenenfalls korrigierte Vergleichsgrößen werden getrennt ausgewiesen.

## 8. Flugprofil und Vergleichbarkeit

Die im Hauptprotokoll beschriebenen Ost-West-Flüge, Geschwindigkeitsvariationen und Referenzstationen bilden die Ausgangsbasis. Für die technische Auslegung sind Fluggeschwindigkeit gegenüber der Luft, Geschwindigkeit über Grund und gegebenenfalls Geschwindigkeit in einem erdzentrierten Bezugssystem ausdrücklich auseinanderzuhalten.

Empfohlen werden vorab dokumentierte Kalibrierungsflüge, Wiederholungen, vertauschte Flugrichtungen und, soweit praktisch möglich, ein Austausch der Messinstrumente zwischen den Flugzeugen. Unterschiede der gravitativen Potentiale, Flugbahnen und Beschleunigungsphasen sind im Unsicherheitsbudget zu berücksichtigen.

## 9. Messunsicherheitsbudget und wissenschaftliche Prüfung

Für jede primäre Messgröße ist ein nachvollziehbares Unsicherheitsbudget zu erstellen. Mindestens zu prüfen sind:
- Uhrendrift und systematische Frequenzverschiebungen;
- Laser- und Referenzstabilität;
- Temperatur-, Druck-, Magnetfeld- und Beschleunigungsempfindlichkeit;
- Zeitstempel-, Synchronisations- und Übertragungsfehler;
- Position, Flughöhe, Geschwindigkeitsbestimmung und Flugbahnabweichungen;
- gemeinsame systematische Fehler beider Flugzeuge.

Die Rohdaten werden unverändert archiviert. Die erste Sichtung darf ohne theoretische Anpassung erfolgen. **Eine quantitative Aussage über Gleichheit, Abweichung oder theoretische Bestätigung setzt jedoch eine definierte Vergleichsgröße, statistische Auswertung und Unsicherheitsbetrachtung voraus.** Vor dem Experiment sind unterscheidbare Vorhersagen der konkurrierenden Hypothesen festzulegen.

## 10. Wiederverwendbare Forschungsinfrastruktur

Die beiden Flugzeuge sollen nach der ersten Messkampagne auch anderen Forschungsgruppen zur Verfügung stehen. Eine modulare, dokumentierte Instrumentenintegration ermöglicht Wiederholungen, alternative Messgeräte und neue Fragestellungen. Offene Rohdaten, Kalibrierdateien, Schnittstellenbeschreibungen und Auswertungsprotokolle erleichtern die unabhängige Überprüfung.

Die Wiederholung mit denselben Flugzeugen ist eine Replikation unter vergleichbaren Bedingungen. Eine zusätzliche Überprüfung mit anderen Instrumenten oder Plattformen kann gemeinsame systematische Fehler besser aufdecken.

## 11. Offene Entscheidungen

1. Eignung des Airbus A350-900 gegenüber Alternativen.
2. Zulassungs- und Sicherheitskonzept für die Umbauten.
3. Konkrete Sensorik, Instrumentenbefestigung und Schwingungsisolierung.
4. Auswahl der Atomuhren und Lasertechnologie.
5. Verfahren zum Vergleich räumlich getrennter Uhren.
6. Erforderliche Messdauer, Messunsicherheit und Flugprofil.
7. Datenformate, Kalibrierungen und unabhängige Replikationsstrategie.
8. Kosten, Betrieb und Zugang für weitere Forschungsteams.

## 12. Vorläufige Kohärenzprüfung

**Technisch plausibel als Konzept:** baugleiche Flugzeuge, inertiale Überwachung, Schwingungsisolierung, lokale Datenerfassung und wiederverwendbare Messmodule.

**Noch nicht nachgewiesen:** Eignung des A350 als optimale Plattform; erreichbare Zeit- und Frequenzvergleichsgenauigkeit; Trennschärfe der Hypothesentests; konkrete Zulassungsfähigkeit und Kosten.

**Methodische Grenze:** Lokal erfasste Messreihen können ohne eine geeignete physikalische Vergleichsprozedur nicht allein durch identische Marker-IDs zu einer eindeutig synchronisierten gemeinsamen Zeitachse werden. Diese offene Frage ist vor einer belastbaren Schlussfolgerung experimentell zu lösen.

## 13. Weiterführende technische Referenzen

- EASA, Type Certificate Data Sheet A.151 – Airbus A350: https://www.easa.europa.eu/en/document-library/type-certificates/aircraft-cs-25-cs-22-cs-23-cs-vla-cs-lsa/easaa151-airbus-a350
- Deutsches Zentrum für Luft- und Raumfahrt (DLR), Entwicklungsbetrieb für Forschungsflugzeuge: https://www.dlr.de/de/fx/ueber-uns/abteilungen/entwicklungsbetrieb
- Airbus, Test and Certification: https://www.airbus.com/en/products-services/commercial-aircraft/the-life-cycle-of-an-aircraft/test-and-certification

---

*Dieser Anhang ergänzt die bestehende Gegenhypothese und Versuchsanweisung. Er ersetzt weder das Hauptprotokoll noch eine detaillierte Systemauslegung oder eine behördliche Zulassung.*
