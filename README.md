semmelhaack-zvbn/gtfs_r# GTFS Realtime VBN
Auswertung der VBN GTFS Realtime Daten

## Laden von GTFS Daten
- Variablen für Pfade / Dateien finden sich im .env File
- Auswertungen
  - Ermittlung der Linien im VBN über Verknüpfung der Haltestellen mit den VBN-Grenzen
  - Ermitteln der Fahrten die an einem bestimmten Tag verkehren


## VBN GTFS Realtime
- JSON http://gtfsr.vbn.de/gtfsr_connect.json
- Protobuf http://gtfsr.vbn.de/gtfsr_connect.bin

## GTFS Realtime Format
Format https://gtfs.org/resources/gtfs-realtime/
Python Bibliotheken https://github.com/MobilityData/gtfs-realtime-bindings/tree/master/python
