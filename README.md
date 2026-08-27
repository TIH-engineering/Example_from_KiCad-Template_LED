# Example_from_KiCad-Template_LED

[![release](https://img.shields.io/github/v/release/TIH-engineering/Example_from_KiCad-Template_LED?label=release)](https://github.com/TIH-engineering/Example_from_KiCad-Template_LED/releases)
[![Build](https://github.com/[GITHUB_USER]/[REPOSITORY]/actions/workflows/build.yml/badge.svg)](https://github.com/TIH-engineering/Example_from_KiCad-Template_LED/actions/workflows/build.yml)
![Hardware](https://img.shields.io/badge/Hardware-KiCad-blue)
![License](https://img.shields.io/badge/License-CC--BY--NC--SA--4.0-lightgrey)

## 🔌 Leiterplattenbeschreibung

Die Leiterplatte **Example_from_KiCad-Template_LED** wurde als Beispiel zur Nutzung des KiCad-Templates erstellt.

Das Beispiel dient als Vorlage, wie das Template verwendet werden kann und wie dann ein Beispielprojekt ausschauen kann.

### Funktionen

- einfache LED-Schaltung - dient nur als Beispiel

> **Einsatzgebiet:** Beispielprojekt

---

## 📥 Downloads

| Datei | Beschreibung |
|---|---|
| 📄 [Schaltplan (PDF)](../../releases/latest/download/schematic.pdf) | Schaltplan der Leiterplatte |
| 🖨️ [Leiterplatte (PDF)](../../releases/latest/download/pcb.pdf) | Leiterplattenansicht als PDF |
| 🔩 [Bohrplan (PDF)](../../releases/latest/download/drill.pdf) | Bohrdaten / Bohrplan |
| 📋 [Stückliste (Excel)](../../releases/latest/download/bom.xlsx) | Bill of Materials |
| 🌐 [Interactive BOM](../../releases/latest/download/ibom.html) | Interaktive Bestückungsansicht |
| 📦 [Fertigungsdaten](../../releases/latest/download/kicad.zip) | Gerber- und Bohrdaten |
| 🧊 [STEP-Modell](../../releases/latest/download/pcb.step) | 3D-Modell der Leiterplatte |

Die Dateien werden automatisch durch den Release-Workflow erzeugt.

---

## 🖥️ Leiterplatte

### Vorschau

| Oberseite | Unterseite |
|:---:|:---:|
| ![PCB Top](../../releases/latest/download/top.kicad.thumbnail.png) | ![PCB Bottom](../../releases/latest/download/bottom.kicad.thumbnail.png) |

### Oberseite

![PCB Top](../../releases/latest/download/top.kicad.png)

### Unterseite

![PCB Bottom](../../releases/latest/download/bottom.kicad.png)

---

## ℹ️ Projektinformationen

| Eigenschaft | Wert |
|---|---|
| **Projekt** | Example_from_KiCad-Template_LED |
| **Software** | KiCad 10 |
| **Repository** | TIH-engineering/Example_from_KiCad-Template_LED |
| **Autor** | TIH |
| **Lizenz** | CC BY-NC-SA 4.0 |

---

## 🗂️ Repository-Struktur

```text
.
├── .github/
│   └── workflows/       # GitHub Actions
├── .kibot/              # KiBot-Konfiguration
├── images/              # Bilder und Renderings
├── pcb/
│   ├── lib/             # Projektspezifische Bibliotheken
│   └── ...              # KiCad-Projektdateien
├── .gitignore
├── LICENSE
└── README.md