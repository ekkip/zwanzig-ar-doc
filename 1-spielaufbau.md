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

Es werden alle Geschichten (auch als Touren oder "Zeitreisen" bezeichnet) angezeigt, die im (einzigen) Content-Eintrag des Typs [CP 0: Game](2.1-cms-struktur.html#cp0-game) gelistet sind. Die User*in kann anhand der Teasertexte (1.3), Tourlängen (1.4) und der jeweiligen Entfernung zum ersten Portal eine informierte Entscheidung für eine Tour treffen.

![Tourauswahl](/img/2_tourauswahl.png)

- [CP 1: Geschichte](2.1-cms-struktur.html#cp1-geschichte)
    - Bild für Tourauswahl (<a name="1.1-bild-fuer-tourauswahl">1.1</a>)
    - Titel (<a name="1.2-titel">1.2</a>)
    - Text für Tourauswahl (<a name="1.3-text-fuer-tourauswahl">1.3</a>)
    - Tourlänge (<a name="1.4-tourlaenge">1.4</a>)

## AR-Session (Tourbeginn)

Nach Auswahl einer Tour beginnt unmittelbar die erste AR-Session ad-hoc. Nach Durchschreiten des erschienenen Portals wird zunächst die Anmoderation (2.2) und dann das erste Navigationsartefakt (2.3) eingesammelt.

![AR-Session Tourbeginn 1](/img/3_ar-session-tourbeginn-1.png) ![AR-Session Tourbeginn 2](/img/3_ar-session-tourbeginn-2.png)

- [CP 1: Geschichte](2.1-cms-struktur.html#cp1-geschichte)
    - Titel (<a name="2.1-titel">2.1</a>)
    - Anmoderation (<a name="2.2-anmoderation">2.2</a>)
    - Einstiegs-Linkobjekttyp (<a name="2.3-einstiegs-linkobjekttyp">2.3</a>)

## Spielplan

Nachdem das erste Navigationsartefakt (auch Linkobjekt) eingesammelt wurde, gelangt die User*in zum Spielplan. Durch Aktivieren des Navigationsartefakts startet der Navigator.

![Spielplan](/img/4_spielplan.png)

- [CP 1: Geschichte](2.1-cms-struktur.html#cp1-geschichte)
    - Titel (<a name="3.1-titel">3.1</a>)
    - Linkobjekttyp (<a name="3.2-linkobjekttyp">3.2</a>)

Navigationsartefakte, die später in den Portalen gefunden werden, ersetzen jeweils das aktuelle Artefakt ([3.2](#3.2-linkobjekttyp)).

## Navigator

Es gibt 3 Arten von Navigations-Artefakten:

- Magischer Kompass und Pharus-Nadel stellen eine direkte Navigation zum nächsten Portal dar.

![Navigator Magischer Kompass](/img/5_navigator-2.png) ![Navigator Pharus-Nadel](/img/5_navigator-3.png)

- Das Hinweis-Artefakt sollte einen inhaltlichen Hinweis auf den Portal-Ort enthalten, auf die letzten Meter kommt eine Radar-Ansicht zu Hilfe. Das Hinweis-Artefakt kann auf ein anderes Navigations-Artefakt gedowngradet werden.

![Navigator Hinweis-Artefakt](/img/5_navigator-1.png) ![Navigator Radar](/img/5_navigator-1b.png)

- [CP 4: Hinweisobjekt](2.1-cms-struktur.html#cp4-hinweisobjekt)
    - Media (<a name="4.1-media">4.1</a>): 2 Bilder (Vorder- und Rückseite)

## AR-Session (regulär)

Wurde der Ort gefunden (GPS-Genauigkeit) öffnet sich die AR-Session. Die User*in hat nun die Aufgabe, den Einstiegspunkt der Worldmap zu finden. Hierzu gibt es zunächst einen textlichen (5.1), bei Bedarf auch einen bildlichen Hinweis (6.1).

![AR-Session Hint Text](/img/6_ar-session-1a.png) ![AR-Session Hint Image](/img/6_ar-session-1b.png)

- [CP 2: Portal](2.1-cms-struktur.html#cp2-portal)
    - Hint Text (<a name="5.1-hint-text">5.1</a>)
    - Hint Image (<a name="5.2-hint-image">5.2</a>)

Sobald die Worldmap gefunden wurde, wird zunächst das Portal platziert. Nach dessen Durchschreitung erscheint die Portal-Einführung (5.3, 5.4).

![AR-Session Portal Titel](/img/6_ar-session-2a.png) ![AR-Session Portalspezifische Story](/img/6_ar-session-2b.png)

- [CP 2: Portal](2.1-cms-struktur.html#cp2-portal)
    - Titel (<a name="5.3-titel">5.3</a>)
    - Portalspezifische Story (<a name="5.4-portalspezifische-story">5.4</a>)

Beim anschließenden Einsammeln der Objekte erscheint die Objektbeschreibung fürs Sammelalbum (5.5, 5.6, 5.7), das Objekt (5.8) erhält ein Titel-Label (5.6).

![AR-Session Objektspezifische Story](/img/6_ar-session-3a.png) ![AR-Session Objekt](/img/6_ar-session-3b.png)

- [CP 3: Objekt](2.1-cms-struktur.html#cp3-objekt)
    - Media (<a name="5.5-vorschau">5.5</a>): Vorschaubild (nur bei 3D-Objekten als zusätzliches 2D-Bild zu ergänzen)
    - Titel (<a name="5.6-titel">5.6</a>)
    - Objektspezifische Story (<a name="5.7-objektspezifische-story">5.7</a>)
    - Media (<a name="5.8-objekt">5.8</a>): eigentliches Objekt

![AR-Session Navigationsartefakt](/img/6_ar-session-4a.png)

- [CP 3: Objekt](2.1-cms-struktur.html#cp3-objekt)
    - Linkobjekttyp (<a name="5.9-linkobjekttyp">5.9</a>) außer letztes Portal


## Sammelalbum

Die im Spielverlauf aufgefundenen Inhalte sind im Sammelalbum jederzeit wieder abrufbar. Das Sammelalbum besteht aus einer ersten und letzten Seite für die An- und Abmoderation der Geschichte sowie je einer Seite für jedes besuchte Portal, auf der die portalspezifischen Inhalte zusammengefasst sind.

### Erste und letzte Seite

![Sammelalbum Start](/img/7_sammelalbum-1.png) ![Sammelalbum Ende](/img/7_sammelalbum-2.png)

- [CP 1: Geschichte](2.1-cms-struktur.html#cp1-geschichte)
    - Bild für Tourauswahl (<a name="6.1-bild-fuer-tourauswahl">6.1</a>)
    - Titel (<a name="6.2-titel">6.2</a>)
    - Anmoderation (<a name="6.3-anmoderation">6.3</a>)
    - Abmoderation (<a name="6.4-abmoderation">6.4</a>)

### Portalseite

Die Portalseite beginnt mit portalspezifischen Inhalten, darunter folgen absatzweise die Inhalte zu den im Portal gesammelten Objekten und der jeweils stiftenden Institution.

![Sammelalbum Portalseite Kopf](/img/8_sammelalbum-portal-1.png)

- [CP 2: Portal](2.1-cms-struktur.html#cp2-portal)
    - Bild für Sammelalbum (<a name="7.1-bild-fuer-sammelalbum">7.1</a>)
    - Titel (<a name="7.2-titel">7.2</a>)
    - Portalspezifische Story (<a name="7.3-portalspezifische-story">7.3</a>)

![Sammelalbum Portalseite Objekt-Absatz](/img/8_sammelalbum-portal-2.png)

- [CP 3: Objekt](2.1-cms-struktur.html#cp3-objekt)
    - Media (<a name="7.4-media">7.4</a>): Vorschaubild (nur bei 3D-Objekten als zusätzliches 2D-Bild zu ergänzen)
    - Titel (<a name="7.5-titel">7.5</a>)
    - Objektspezifische Story (<a name="7.6-objektspezifische-story">7.6</a>)
    - zum Teilen freigegeben ja/nein (<a name="7.7-zum-teilen-freigegeben">7.7</a>)

- [CP 4: Institution](2.1-cms-struktur.html#cp5-institution)
    - Titel (<a name="7.8-titel">7.8</a>)
    - Logo (<a name="7.9-logo">7.9</a>)
