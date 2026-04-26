# Radiomaster T8L Analog Mod

## The goal
*Have you ever wanted to have an analog screen built into you fpv radio ?*

Thats what we want to do without the hassle of designing a whole radio.

This project is based around the Radiomaster T8L.

## Our discord server
https://discord.gg/dHFfaPaWNn

## The roadmap
*The roadmap is right now made for the two first versions but may change/update depending of the progress.*

```mermaid
sequenceDiagram
Base idea ->> First design: Choice of components, BOM, CAD (4 weeks)
First design ->> First version: Tests, assembly, production (2 weeks)
First version -->> Base idea: Feedback (~1 week)
Base idea ->> Adjustments: Redesign/changes, updates (3 weeks)
Adjustments ->> Second version: Tests, assembly, production (2 weeks)
Second version -->> Base idea: Feedback (~1 week)
```

## Wiring diagram
*This is the current version's wiring diagram.*

```mermaid
graph LR
A[2x 21700]
B[T8L Motherboard]
D[Screen]
E[Analog VRX]
F[5v BEC]
G[12v booster]
H[Switch]

A --> B
A --> F
A --> G
G --> H --> D
F --> H --> E
```

## Bill Of Material (BOM)
*The current BOM for this build is:*
- Radiomaster T8L
- 4/3" AV in display
- 12v booster
- 2x 18650 or 2x 21700 battery
- Switch to turn on/off the screen
- 5v BEC
- Analog VRX of your choice
