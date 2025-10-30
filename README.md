# RPG (Godot Engine Projekt)

Dies ist ein **2D-RPG-Projekt**, das mit der **Godot Engine 4** entwickelt wird.  
Das Spiel befindet sich noch in der **Entwicklungsphase** und konzentriert sich derzeit auf den Aufbau der **Kernsysteme für Spieler und Welt**.

## 🎮 Aktueller Entwicklungsstand

- **Flüssige Spielerbewegung** mit `CharacterBody2D`
- **Richtungsspezifisches Animationssystem** (Idle, Walk, Up, Down, Side)
- **Interaktionssystem** zwischen Spieler und Umgebung (`PlayerInteractionsHost`)
- **Level-Management-System** (`GlobalLevelManager`) zur Verwaltung von Tilemap-Grenzen und Level-Übergängen
- Saubere und modulare GDScript-Struktur

## 🧩 Projektstruktur


├── project.godot
├── playground.tscn
├── scripts/
│ ├── Player.gd
│ ├── PlayerInteractionsHost.gd
│ ├── LevelTileMap.gd
│ ├── GlobalLevelManager.gd
│ └── ...
└── assets/
├── sprites/
├── sounds/
└── tiles/


## 🚧 Geplante Features

- Kampfsystem  
- NPC-Interaktionen  
- Dialogsystem  
- Karten- und Quest-Übergänge  

## 🛠️ Engine

- **Godot Engine 4.x**  
- Programmiersprache: **GDScript**

## 💡 Autor

Entwickelt von **Amine EL KHATTABI**  
*(In Arbeit – Lern- und Prototyp-Projekt)*
