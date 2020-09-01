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

Es werden alle Geschichten (auch als Touren oder "Zeitreisen" bezeichnet) angezeigt, die im (einzigen) Content-Eintrag des Typs [CP 0: Game](2-cms.html#cp0-game) gelistet sind. Die User*in kann anhand der Teasertexte (1.3), Tourlängen (1.4) und der jeweiligen Entfernung zum ersten Portal eine informierte Entscheidung für eine Tour treffen.

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

- Magischer Kompass und Pharus-Nadel stellen eine direkte Navigation zum nächsten Portal dar.

![Navigator Magischer Kompass](/img/5_navigator-2.png) ![Navigator Pharus-Nadel](/img/5_navigator-3.png)

- Das Hinweis-Artefakt gibt einen inhaltlichen Hinweis auf den Portal-Ort, auf die letzten Meter kommt eine Radar-Ansicht zu Hilfe. Das Hinweis-Artefakt kann auf ein anderes Navigations-Artefakt gedowngradet werden.

![Navigator Hinweis-Artefakt](/img/5_navigator-1.png) ![Navigator Radar](/img/5_navigator-1b.png)

- [CP 4: Hinweisobjekt](2-cms.html#cp4-hinweisobjekt)
    - Media ([4.1](#4.1-media)): 2 Bilder (Vorder- und Rückseite)

## AR-Session (regulär)

Wurde der Ort gefunden (GPS-Genauigkeit) öffnet sich die AR-Session. Die User*in hat nun die Aufgabe, den Einstiegspunkt der Worldmap zu finden. Hierzu gibt es zunächst einen textlichen (5.1), bei Bedarf auch einen bildlichen Hinweis (6.1).

![AR-Session Hint Text](/img/6_ar-session-1a.png) ![AR-Session Hint Image](/img/6_ar-session-1b.png)

- [CP 2: Portal](2-cms.html#cp2-portal)
    - Hint Text ([5.1](#5.1-hint-text))
    - Hint Image ([5.2](#5.1-hint-image))

Sobald die Worldmap gefunden wurde, wird zunächst das Portal platziert. Nach dessen Durchschreitung erscheint die Portal-Einführung (5.3, 5.4).

![AR-Session Portal Titel](/img/6_ar-session-2a.png) ![AR-Session Portalspezifische Story](/img/6_ar-session-2b.png)

- [CP 2: Portal](2-cms.html#cp2-portal)
    - Titel ([5.3](#5.3-titel))
    - Portalspezifische Story ([5.4](#5.4-portalspezifische-story))

Beim anschließenden Einsammeln der Objekte erscheint die Objektbeschreibung fürs Sammelalbum (5.5, 5.6, 5.7), das Objekt (5.8) erhält ein Titel-Label (5.6).

![AR-Session Objektspezifische Story](/img/6_ar-session-3a.png) ![AR-Session Objekt](/img/6_ar-session-3b.png)

- [CP 3: Objekt](2-cms.html#cp3-objekt)
    - Media ([5.5](#5.5-media)): Vorschaubild (nur bei 3D-Objekten als zusätzliches 2D-Bild zu ergänzen)
    - Titel ([5.6](#5.6-titel))
    - Objektspezifische Story ([5.7](#5.7-objektspezifische-story))
    - Media ([5.8](#5.3-titel)): eigentliches Objekt

![AR-Session Navigationsartefakt](/img/6_ar-session-4a.png)

- [CP 3: Objekt](2-cms.html#cp3-objekt)
    - Linkobjekttyp ([5.9](#5.9-linkobjekttyp)) außer letztes Portal


## Sammelalbum

Die im Spielverlauf aufgefundenen Inhalte sind im Sammelalbum jederzeit wieder abrufbar. Das Sammelalbum besteht aus einer ersten und letzten Seite für die An- und Abmoderation der Geschichte sowie je einer Seite für jedes besuchte Portal, auf der die portalspezifischen Inhalte zusammengefasst sind.

### Erste und letzte Seite

![Sammelalbum Start](/img/7_sammelalbum-1.png) ![Sammelalbum Ende](/img/7_sammelalbum-2.png)

- [CP 1: Geschichte](2-cms.html#cp1-geschichte)
    - Bild für Tourauswahl (<a href="#6.1-bild-fuer-tourauswahl">6.1</a>)
    - Titel ([6.2](#6.2-titel))
    - Anmoderation ([6.3](#6.3-anmoderation))
    - Abmoderation ([6.4](#6.4-abmoderation))

### Portalseite

Die Portalseite beginnt mit portalspezifischen Inhalten, darunter folgen absatzweise die Inhalte zu den im Portal gesammelten Objekten und der jeweils stiftenden Institution.

![Sammelalbum Portalseite Kopf](/img/8_sammelalbum-portal-1.png)

- [CP 2: Portal](2-cms.html#cp2-portal)
    - Bild für Sammelalbum ([7.1](#7.1-bild-fuer-sammelalbum))
    - Titel ([7.2](#7.2-titel))
    - Portalspezifische Story ([7.3](#7.3-portalspezifische-story))

![Sammelalbum Portalseite Objekt-Absatz](/img/8_sammelalbum-portal-2.png)

- [CP 3: Objekt](2-cms.html#cp3-objekt)
    - Media ([7.4](#7.4-media)): Vorschaubild (nur bei 3D-Objekten als zusätzliches 2D-Bild zu ergänzen)
    - Titel ([7.5](#7.5-titel))
    - Objektspezifische Story ([7.6](#7.6-objektspezifische-story))
    - zum Teilen freigegeben ja/nein ([7.7](#7.7-zum-teilen-freigegeben))

- [CP 4: Institution](2-cms.html#cp5-institution)
    - Titel ([7.8](#7.8-titel))
    - Logo ([7.9](#7.9-titel))
