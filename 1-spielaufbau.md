---
title: Spielaufbau
parent: Übersicht
nav_order: 1
---

# Spielaufbau

## Intro

![Intro](/img/1_intro_small_.png)

Die mehrseitige Intro muss einmal durchgeblättert werden, von hier gelangt die User*in automatisch zur Tourauswahl.

## Tourauswahl

![Tourauswahl](/img/2_tourauswahl_small.png)

- CP 0: App
    - Geschichten [CP 1]  
- CP 1: Geschichte
    - Titel
    - Bild für Tourauswahl
    - Text für Tourauswahl
    - Tourlänge [Minuten]

## AR-Session (Tourbeginn)

- CP 1: Geschichte
    - Anmoderation
    - Einstiegs-Linkobjekttyp

## Spielplan

- CP 1: Geschichte
    - Portale [CP 2]
        - Standort

## Navigator

- CP 1: Geschichte
    - Einstiegs-Linkobjekttyp, ggfs. CP 4: Hinweisobjekt (für erstes reguläres Portal)
- CP 2: Portal
    - Standort
    - Linkobjekttyp, ggfs. CP 4: Hinweisobjekt (ab zweitem regulären Portal)

## AR-Session (regulär)

- CP 2: Portal
    - Hint Text
    - Hint Image
    - World Map
    - Portalspezifische Story
    - Objekte [CP 3]
        - Titel
        - Asset
        - Container
        - Objektspezifische Story
        - Containertyp, ggfs. Long Dimension (Containertyp “Paper” und “Film”)
        - Fragmentation
    - Linkobjekttyp, ggfs. CP 4: Hinweisobjekt (außer letztes Portal)
- CP 1: Geschichte
    - Abmoderation (nur im letzten Portal)


## Sammelalbum

### Erste und letzte Seite
- CP 1: Geschichte
    - Titel
    - Bild für Tourauswahl
    - Anmoderation
    - Abmoderation

### Portalseite
- CP 2: Portal
    - Bild für Sammelalbum
    - Titel
    - Portalspezifische Story
    - Standort
    - Objekte [CP 3]
        - Asset (Besonderheiten Vorschaubild!)
        - Titel
        - Objektspezifische Story
        - Stiftende Organisation [CP 5]
            - Titel
            - Logo
        - zum Teilen freigegeben ja/nein
