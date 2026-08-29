# Gcode-Analyzer

Gcode-Dateien vor dem Druck prüfen, ohne den Slicer zu öffnen: Abmessungen, Layer-Anzahl, Filament-Verbrauch und Druckzeit-Schätzung – direkt im Browser.

## Features

- Datei laden per **Drag & Drop** oder Datei-Auswahl (`.gcode`, `.gco`, `.g`)
- Bounding-Box (Breite / Tiefe / Höhe des Drucks)
- Layer-Anzahl (erkannte Z-Höhen mit Extrusion)
- Filament-Länge aus den E-Werten (inkl. `G92 E0`-Resets, absolute + relative Extrusion)
- Druckzeit-Schätzung aus Bewegungslänge und Feedrate
- **Top-Down-Vorschau** der Extrusionspfade auf Canvas (bei riesigen Dateien automatisch ausgedünnt)
- Die Datei verlässt den Rechner nie – 100 % clientseitig

## Stack

Vanilla JavaScript, HTML, CSS, Canvas 2D – keine Build-Kette, keine Libraries.

## Setup & Start

```
index.html im Browser öffnen und eine .gcode-Datei hineinziehen.
```

## Screenshot

_(Screenshot folgt)_
