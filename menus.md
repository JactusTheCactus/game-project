```mermaid
---
config:
    flowchart:
        htmlLabels: false
---
flowchart TD
root("Main")
root ==> shop(🛒)
root ==> new(New Game)
root ==> cont(Continue)
root ==> load(Load Game)
shop ==> Weapons
shop ==> Upgrades
shop ==> Power-Ups
root ==> settings(⚙)
settings ==> Language
settings ==> Audio
settings ==> Video
```