## Einführung
- CPU (Central Processing Unit)
- Ausführen von Befehlen
- Verarbeitung von Daten

## Funktionsweise
- Dekodiert Befehle aus dem Arbeitsspeicher zu Anweisungen
- Steuerwerk 
	- leitet Anweisungen an verschiedene Einheiten weiter
- Rechenwerk
	- Ausführung von Addition, Subtraktion, Multiplikation und Division
- Verwaltet Zugriff auf Arbeits- und Cache-Speicher
	- lesen und schreiben der Daten
- Ausführung Milliardenfach pro Sekunde (Taktfrequenz)

## Cache
- Schneller Puffer-Speicher zwischen CPU und RAM
- Laden von Datenblöcken in Cache zur Verarbeitung
- Zugriff auf Arbeitsspeicher, wenn Cache abgearbeitet ist
- Mehrstufiger Cache
	- Je näher an der CPU, desto schneller
	- L1 
		- speichert nötigste Befehle
	- L2
		- speichert Befehle aus dem Arbeitsspeicher
	- L3
		- Datenaustausch zwischen Kernen
![[Pasted image 20250108191815.png]]

## Overclocking
- Anzahl der Abläufe pro Sekunde (in Hz)
- Je höher die Frequenz, desto mehr Abläufe
- Erhöhte Wärmeentwicklung
- BIOS/UEFI Einstellungen werden geändert
- Kompatibilität


## Parallelisierung
- Pipelining
	- Aufteilung unterschiedlicher Befehle in Arbeitsteile mit gleicher Bearbeitung
	- Arbeitsteile als Art Fließband abgearbeitet
	- Zusammenfassung: Vermeidung des Wartens bis ein vorheriger Prozess beendet ist durch Bearbeitung gleicher Arbeitsteile unterschiedlicher Befehle
- Coprozessor
	- Speziell, um den Hauptprozessor bei manchen Funktionen zu entlasten
- Multi-Prozessor
- Multi-Core-Prozessor
- Multi-Threading

## Multi-Threading
- Aufteilung der Arbeit auf mehrere Threads
- Thread wartet auf Speicherzugriff -> Anderer Thread macht weiter
- Gleichzeitige Abarbeitung von Threads
- Hyper-Threading
	- Teilung des physischen Kerns in zwei logische Kerne