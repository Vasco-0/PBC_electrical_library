# ⚡ Portugal Boat Challenge — Electrical Harness Library  
### Standardized symbols & templates for compliant schematics

This repository provides **official-style schematic libraries and documentation templates** to help teams competing in the **Portugal Boat Challenge** prepare electrical and harness documentation that complies with event safety and technical review standards.

The goal of this library is to ensure all teams present electrical systems clearly, safely, and consistently — supporting **judges, inspectors, and team collaboration**.

---

## 🎯 Purpose

This library helps teams:

✅ Use a uniform symbol language across the competition  
✅ Clearly document electric vessel systems  
✅ Communicate safety circuits to judges & inspectors  
✅ Reduce ambiguity in electrical submissions  
✅ Improve clarity & professionalism of schematics  

---

## 📦 Contents

| Folder | Description |
|--------|------------|
| `/Altium/` | Competition symbols for Altium Designer |
| `/KiCad/` | Competition symbols for KiCad |
| `/Preview/` | PNG/SVG previews of schematic symbols |
| `/Docs/` | Symbol naming conventions & usage notes |

---

## 🧩 Included Symbol Types

| Category | Examples |
|---------|----------|
| Power & Energy Functions| Solar panel, Battery pack, Relays, MPPT ...|
| Safety Functions | E-Stop, Dead-man switch, Fuse, Breaker, ...|
| Others | Antennas, Shunts, ... | 

---

## 🚀 Using the Library

### Altium
- Import the `.SchLib`
- Place components in your system diagram

### KiCad
- Add the `.kicad_sym` file to your global/project libraries

### Other Tools
- Use symbols from `/Other` or `/Preview` folders
- Or create equivalents based on the provided references

---

### Required Wire Color Coding

All teams must follow consistent wire colors to ensure clarity and compliance:

| Voltage Type | Meaning | Color |
|-------------|--------|-------|
| **Unregulated Battery Voltage** | Direct battery output used for propulsion | **Red (+)** |
| **Regulated DC Bus Voltage** | Voltage conditioned by converters  | **Orange (+)** |
| **PV DC Voltage** | Direct output from PV panels  | **Yellow (+)** |
| **Ground**  | Electrical reference point | **Black** |
| Safety / E-Stop circuit | - | **Bright Purple** |
| Sensor / Signal | - | **Blue** |


## 🌍 Contribution Guidelines

We welcome contributions to extend symbol coverage:

- Submit only **schematic symbols**
- Follow naming and style rules in `/Docs/Symbol_Guidelines.md`
- Include a preview (.png or .svg) for each new symbol

To contribute:

1. Fork the repo  
2. Add your symbols  
3. Submit a PR with explanation  

---

## 📜 License

MIT License — freely usable for **Portugal Boat Challenge** teams and educational purposes.

---

## ⭐ Credit & Motivation

Created to support the Portugal Boat Challenge community  
and promote standardized, safe, and clear electric-boat engineering.

If this library helps your team, please ⭐ star the repo and share improvements!

---

## 📧 Contact

Questions or suggestions?  
Open an issue or contact the maintainers.
