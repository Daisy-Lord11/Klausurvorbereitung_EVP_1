## Was ist ein Laufwerk

- Gerät, dass zum Lesen, Schreiben und Speichern von Daten auf einem Datenträger verwendet wird


# Fachbegriffe & Spezifikationen

## Leistungsmerkmale

- Zugriffszeit & Transferrate
- Abhängig von Umdrehungen und Schnittstelle
- Umdrehungsgeschwindigkeit (HDD)
	- Bspw. 5400 rpm (revolutions per minute)
- Cache
	- 16-64 MB (Standard)
	- 64-128 MB (High-Performance)

## Festplattenpartitionierung

- Erhöhte Datensicherheit
	- Datenverlust einer Partition beeinflusst nicht das ganze Speichermedium
- Mehrere Betriebssysteme
	- Man kann mehrere Betriebssysteme auf verschiedenen Partitionen erstellen
- Effiziente Nutzung für Backups und Wartung
	- Parallel Arbeit während auf einer anderen Partition ein Backup erstellt wird

## Schnittstellen & Bandbreite

- SATA: 
	- Standard, 150-600 MB/s
- PCIe 3.0 & 4.0: 
	- Höhere Bandbreite, bis 16 Gbit/s
- PCIe: x4, x8, x16:
	- Bis zu 8 GB/s

## Flash-Speicher

- Nicht-Flüchtiger-Speicher: 
	- Daten bleiben ohne Strom gespeichert
	- Speicherung in Speicherzellen


## HDD

![[Pasted image 20250111163933.png]]

- ziemlich alt und dennoch relevant
- Bauformen
	- 1.8" / 2.5" -> Notebooks
	- 3.5"          -> Desktop

Speicherung:
Speicherung durch die Heads auf einer sich drehenden, magnetischen Metallscheibe


| Vorteile                                                  | Nachteile                                                 |
| --------------------------------------------------------- | --------------------------------------------------------- |
| Billig                                                    | Anfällig gegenüber Magnetismus                            |
| Weniger Risiko bei stromloser Langzeitspeicherung         | Beweglichkeit der Teile -> Stöße Zerstören Funktionalität |
| Geeigneter für Anwendungen mit kontinuierlichem schreiben | Im Vergleich zu SSD langsamer                             |
| Robustheit bei Hitze (i.V. zu SSD)                        | Höherer Energieverbrauch                                  |
|                                                           | Lauter                                                    |
|                                                           | Wärmebildung bei Stress                                   |


## SSD

- Flash-Speicher ohne bewegliche Teile

Speicherung:
Daten werden in elektrischen Flash-Speicherzellen festgehalten, oft als Bits in MLC 


| Vorteile                            | Nachteile                                              |
| ----------------------------------- | ------------------------------------------------------ |
| hohe Geschwindigkeit                | Höhere Kosten für gleichen Speicherplatz               |
| Robustheit (keine bewegbaren Teile) | Mögliche Datenverluste bei langer Stromtrennung        |
| Energieeffizient                    | Wärmeanfälliger als HDD                                |
| Lautlos                             | Begrenzte Anzahl an Schreibzyklen (Dann unzuverlässig) |
| Meist kleiner                       |                                                        |
| Langlebigkeit im Dauerbetrieb       |                                                        |

## USB-Sticks

- Nutzt schnellen Flash-Speicher
- Lässt sich über USB mit Geräten verbinden


| Vorteile        | Nachteile                                         |
| --------------- | ------------------------------------------------- |
| klein           | Begrenzte Speichergröße aufgrund physischer Größe |
| leise           | Anfällig für Verlust                              |
| mobil           | Geschwindigkeitsbegrenzt                          |
| Wiederbenutzbar |                                                   |
