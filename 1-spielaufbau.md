---
title: Spielaufbau
parent: Übersicht
nav_order: 1
---

# Spielaufbau

## Intro

![Intro](/img/1_intro.png)

Die mehrseitige Intro muss einmal durchgeblättert werden, von hier gelangt die User*in automatisch zur Tourauswahl.

## Tourauswahl

![Tourauswahl](/img/2_tourauswahl.png)

Es werden alle Geschichten angezeigt, die im (einzigen) Content-Eintrag des Typs [CP 0: Game](2-cms.html#cp1-game) gelistet sind.

- [CP 1: Geschichte](2-cms.html#cp2-geschichte)
    - Bild für Tourauswahl [1.1](#1.1-bild-fuer-tourauswahl)
    - Titel [1.2](#1.2-titel)
    - Text für Tourauswahl [1.3](#1.3-text-fuer-tourauswahl)
    - Tourlänge [1.4](#1.4-tourlaenge)

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
