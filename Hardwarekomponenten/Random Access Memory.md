| Abkürzung                | Ausgeschrieben                                            |                   |
| ------------------------ | --------------------------------------------------------- | ----------------- |
| <br>Speichertechnologien |                                                           |                   |
| RAM                      | Random Access Memory                                      |                   |
| DRAM                     | Dynamic Random Access Memory                              |                   |
| SDRAM                    | Synchronous Dynamic Random Access Memory                  |                   |
| DDR-RAM                  | Double Data Rate - Random Acces Memory                    | <br>              |
| DDR-SDRAM                | Double Data Rate Synchronous Dynamic Random Access Memory |                   |
|                          |                                                           |                   |
| Formfaktoren             |                                                           | Formfaktor für... |
| DIMM                     | Dual Inline Memory Modul                                  | PC/Desktop        |
| SO-DIMM                  | Small Outline Dual In Line Memory Modul                   | Laptop            |
| UDIMM                    | Unbuffered Dual Inline Memory Modul                       | PC/Desktop        |

# Speichertechnologien
## DRAM (Dynamic Random Access Memory)

- Jedes Datenbit separater Kondensator gespeichert
- Häufigste Art von Arbeitsspeicher

## SDRAM (Synchronous Dynamic Random Access Memory)

- getaktete DRAM-Technologie
- Daten synchron zum Speicher-Bus übertragen
- Vorgabe des Takts durch
	- System-Bus
	- separate am System-Bus angeschlossenen Speicher-Bus
- Low Power SDRAM für mobile Geräte eine eigene Spezifikation

## DDR-RAM (Double Data Rate)

- Übertragung doppelt so schnell wie SDRAM
- Zahl nach DDR steht für die Generation
- Generationen untereinander nicht kompatibel (Bspw. DDR3 $\neq$ DDR4)
	- DDR
	- DDR2
	- DDR3
	- DDR4
	- DDR5
- Je Taktzyklus zwei Datentransfers (Double Data Rate)

| SO-DIMM      | DDR     | DDR2    | DDR3      | DDR4   | DDR5        |
| ------------ | ------- | ------- | --------- | ------ | ----------- |
| Dichte in GB | 1/2 - 1 | 1/2 - 4 | 1 - 16    | 4 - 32 | 8 - 64 etc. |
| Spannung     | 2.5V    | 1.8V    | 1.35V$^2$ | 1.2V   | 1.1V        |
|              |         |         |           |        |             |
- Geschwindigkeit wird in 
	- MT/s (Megatransfers (million transfers) per second)
	- in MHz (Mega Hertz)
	gemessen

- Dichte wird immer verdoppelt:
	- bspw.  1-64 -> 1GB 2GB 4GB 8GB 16GB 32GB 64GB ...

(Genaue Pinzahl und genaue Geschwindigkeit ausgelassen in der Tabelle... random frage für eine Klausur)

## DDR-SDRAM (Double Data Rate - Synchronous Dynamic Random Access Memory)

- Weiterentwicklung der SDRAM-Technologie
- Hauptsächliche Verwendung der DIMM und SO-DIMM Speichermodule für PCs und Laptops

## SSD-RAM (Solid State Random Access Memory)

- flash-basierter Speicher -> kein Magnetismus 
- Daten bleiben erhalten trotz fehlendem Strom
- SSD als Festplatten verwendet
- Auslagerung bei zu wenig RAM auf Festplatte
- RAM oder SSD prüfen ob upgrade notwendig bei zu wenig RAM... <- idk bei dem...
...dieser ganze Block zu dem Thema SSD-RAM ist weird
-> RAM eig immer schneller als SSD, weshalb eig ne RAM Erweiterung immer besser wäre (wenn möglich)
finde auch nicht direkt iwo eine Bezeichnung/Artikel, die das SSD-RAM nennt :/


## QLC (Quad-Level-Zellen)

- Neuste Technologie in der Speicherarchitektur 
- Speicherung vier Datenbits in jeder Speicherzelle
- Größere Dichte auf kleinerem Raum
(gibt laut Wikipedia seit 2021 schon Penta Quad Cells in der Entwicklung aber vorerst QLC als neustes)

## Latenz

- Zeit für die Reaktion auf ein Befehl
- Je geringer die Zeit, desto schneller


## EEC (Error Correcting Code) RAM

- fully buffered
- häufig in Workstations und Servern
- hilft Speicherfehler zu minimieren / selbständig zu korrigieren

# Siehe FRAGEN von der Präsentation, was bei der Klausur drankommen kann + Abkürzungen ausschreiben