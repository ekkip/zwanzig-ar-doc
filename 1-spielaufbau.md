---
title: Spielaufbau
parent: Übersicht
nav_order: 1
---

# Spielaufbau

## Intro

Die mehrseitige Intro muss einmal durchgeblättert werden, von hier gelangt die User*in automatisch zur Tourauswahl.

![Intro](/img/1_intro.png)

## Tourauswahl

Es werden alle Geschichten angezeigt, die im (einzigen) Content-Eintrag des Typs [CP 0: Game](2-cms.html#cp0-game) gelistet sind.

![Tourauswahl](/img/2_tourauswahl.png)

- [CP 1: Geschichte](2-cms.html#cp1-geschichte)
    - Bild für Tourauswahl ([1.1](#1.1-bild-fuer-tourauswahl))
    - Titel ([1.2](#1.2-titel))
    - Text für Tourauswahl ([1.3](#1.3-text-fuer-tourauswahl))
    - Tourlänge ([1.4](#1.4-tourlaenge))

## AR-Session (Tourbeginn)

Nach Auswahl einer Tour beginnt unmittelbar die erste AR-Session ad-hoc. Nach Durchschreiten des erschienenen Portals wird zunächst die Anmoderation (2.2) und dann das erste Navigationsartefakt (2.3) eingesammelt.

![AR-Session Tourbeginn 1](/img/3_ar-session-tourbeginn-1.png) ![AR-Session Tourbeginn 2](/img/3_ar-session-tourbeginn-2.png)

- [CP 1: Geschichte](2-cms.html#cp1-geschichte)
    - Titel ([2.1](#2.1-titel))
    - Anmoderation ([2.2](#2.2-anmoderation))
    - Einstiegs-Linkobjekttyp ([2.3](#2.3-einstiegs-linkobjekttyp))

## Spielplan

Nachdem das erste Navigationsartefakt eingesammelt wurde, gelangt die User*in zum Spielplan. Durch Aktivieren des Navigationsartefakts startet der Navigator.

![Spielplan](/img/4-spielplan.png)

- [CP 1: Geschichte](2-cms.html#cp1-geschichte)
    - Titel ([3.1](#3.1-titel))
    - Linkobjekttyp ([3.2](#3.2-linkobjekttyp))

## Navigator

Es gibt 3 Arten von Navigations-Artefakten:
- Das Hinweis-Artefakt gibt einen inhaltlichen Hinweis auf den Portal-Ort, auf die letzten Meter kommt eine Radar-Ansicht zu Hilfe. Das Hinweis-Artefakt kann auf ein anderes Navigations-Artefakt gedowngradet werden.
- Magischer Kompass und Pharus-Nadel stellen eine direkte Navigation zum nächsten Portal dar.

![Navigator Hinweis-Artefakt](/img/5_navigator-1.png) ![Navigator Radar](/img/5_navigator-1b.png) ![Navigator Magischer Kompass](/img/5_navigator-2.png) ![Navigator Pharus-Nadel](/img/5_navigator-3.png)

- [CP 4: Hinweisobjekt](2-cms.html#cp4-hinweisobjekt)
    - Media ([4.1](#4.1-media)): 2 Bilder (Vorder- und Rückseite)

## AR-Session (regulär)

- [CP 2: Portal](2-cms.html#cp2-portal)
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
