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

![Spielplan](/img/4_spielplan.png)

- [CP 1: Geschichte](2-cms.html#cp1-geschichte)
    - Titel ([3.1](#3.1-titel))
    - Linkobjekttyp ([3.2](#3.2-linkobjekttyp))

## Navigator

Es gibt 3 Arten von Navigations-Artefakten:
- Das Hinweis-Artefakt gibt einen inhaltlichen Hinweis auf den Portal-Ort, auf die letzten Meter kommt eine Radar-Ansicht zu Hilfe. Das Hinweis-Artefakt kann auf ein anderes Navigations-Artefakt gedowngradet werden.

![Navigator Hinweis-Artefakt](/img/5_navigator-1.png) ![Navigator Radar](/img/5_navigator-1b.png)

- Magischer Kompass und Pharus-Nadel stellen eine direkte Navigation zum nächsten Portal dar.

![Navigator Magischer Kompass](/img/5_navigator-2.png) ![Navigator Pharus-Nadel](/img/5_navigator-3.png)

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

Die im Spielverlauf aufgefundenen Inhalte sind im Sammelalbum jederzeit wieder abrufbar. Das Sammelalbum besteht aus einer ersten und letzten Seite für die An- und Abmoderation der Geschichte sowie je einer Seite für jedes besuchte Portal, auf der die portalspezifischen Inhalte zusammengefasst sind.

### Erste und letzte Seite

![Sammelalbum Start](/img/7_sammelalbum-1.png) ![Sammelalbum Ende](/img/7_sammelalbum-2.png)

- [CP 1: Geschichte](2-cms.html#cp1-geschichte)
    - Bild für Tourauswahl ([6.1](#6.1-bild-fuer-tourauswahl))
    - Titel ([6.2](#6.2-titel))
    - Anmoderation ([6.3](#6.3-anmoderation))
    - Abmoderation ([6.4](#6.4-abmoderation))

### Portalseite

![Sammelalbum Portalseite 1](/img/8_sammelalbum-portal-1.png) ![Sammelalbum Portalseite 1](/img/8_sammelalbum-portal-2.png)

- [CP 2: Portal](2-cms.html#cp2-portal)
    - Bild für Sammelalbum ([7.1](#7.1-bild-fuer-sammelalbum))
    - Titel ([7.2](#7.2-titel))
    - Portalspezifische Story ([7.3](#7.3-portalspezifische-story))

- [CP 3: Objekt](2-cms.html#cp3-objekt)
    - Media (Besonderheiten Vorschaubild!) ([7.4](#7.4-media))
    - Titel ([7.5](#7.5-titel))
    - Objektspezifische Story ([7.6](#7.6-objektspezifische-story))
    - zum Teilen freigegeben ja/nein ([7.7](#7.7-zum-teilen-freigegeben))

- [CP 4: Institution](2-cms.html#cp5-institution)
    - Titel ([7.8](#7.8-titel))
    - Logo ([7.9](#7.9-titel))
