---
title: CMS
parent: Übersicht
has_children: true
nav_order: 2
---

# CMS

Als CMS dient die Headless-CMS-Lösung von [Contentful](https://www.contentful.com).

Sowohl die Spiel-App als auch die Portal Editor Companion App greifen auf das CMS zu.

Jeder CMS-Eintrag ist entsprechend seinem Status in der Spiel-App und in der Portal Editor App unterschiedlich sichtbar:

- __Published__: in beiden Apps sichtbar
- __Changed__: im Portal Editor sichtbar, in der Spiel-App nur im letzten gepublishten Zustand sichtbar
- __Draft__: nur im Portal Editor sichtbar
- __Archived__: in keiner App sichtbar


## CP0: Game

Hiervon sollte nur ein singulärer Eintrag als Ausgangspunkt der Datenbank existieren.

- Titel: Text

- Geschichten: [CP 1: Geschichte](#cp1-geschichte) (mult.)
    - Alle im Spiel zu berücksichtigenden Geschichten müssen hier eingetragen sein.


## CP1: Geschichte

- Titel: Text
    - Ausspielungen: [1.2](1-spielaufbau.html#1.2-titel); [2.1](1-spielaufbau.html#2.1-titel); [3.1](1-spielaufbau.html#3.1-titel); [6.2](1-spielaufbau.html#6.2-titel)

- Anmoderation: [Textobjekt](#textobjekt)
    - Ausspielungen: [2.2](1-spielaufbau.html#2.2-anmoderation); [6.3](1-spielaufbau.html#6.3-anmoderation)

- Abmoderation: [Textobjekt](#textobjekt)
    - Ausspielungen: Ende letzte AR-Session; [6.4](1-spielaufbau.html#6.4-abmoderation)

- Portale: [CP 2: Portal](#cp2-portal) (mult.)

- Einstiegs-Linkobjekttyp: [Linkobjekttyp](#extension-linkobjekttyp)
    - bei Option "Hinweisobjekt" ist zusätzlich ein Hinweisobjekt zu definieren
    - Ausspielungen: [2.3](1-spielaufbau.html#2.3-einstiegs-linkobjekttyp); [3.2](1-spielaufbau.html#3.2-linkobjekttyp)

- Einstiegs-Hinweisobjekt: [CP 4: Hinweisobjekt](#cp4-hinweisobjekt)
    - anzugeben, wenn bei Einstiegs-Linkobjekttyp Option "Hinweisobjekt" eingestellt ist
    - Ausspielungen: [4.1](1-spielaufbau.html#4.1-media)

- Bild für Tourauswahl: Contentful Media Asset
    - Ausspielungen: [1.1](1-spielaufbau.html#1.1-bild-fuer-tourauswahl); [6.1](1-spielaufbau.html#heading-6.1-bild-fuer-tourauswahl)

- Text für Tourauswahl: Text
    - Ausspielungen: [1.3](1-spielaufbau.html#1.3-text-fuer-tourauswahl)

- Tourlänge: Zahl
    - ungefähre Angabe in Minuten
    - Ausspielungen: [1.4](1-spielaufbau.html#1.4-tourlaenge)

- Farbe: [Tour-Farbe](#extension-tour-farbe)


## CP2: Portal

- Titel: Text
    - Ausspielungen: [5.3](1-spielaufbau.html#5.3-titel); [7.2](1-spielaufbau.html#7.2-titel)

- Portalspezifische Story: [Textobjekt](#textobjekt)
    - Ausspielungen: [5.4](1-spielaufbau.html#5.4-portalspezifische-story); [7.3](1-spielaufbau.html#7.3-portalspezifische-story)

- Standort: GPS-Location
    - Eingabe im CMS Texteingabe der Adresse kann genutzt werden, ausschlaggebend ist die Position der Nadel in der Kartendarstellung

- Objekte: [CP 3: Objekt](#cp3-objekt) (mult.)

- Linkobjekttyp: [Linkobjekttyp](#extension-linkobjekttyp)
    - bei Option "Hinweisobjekt" ist zusätzlich ein Hinweisobjekt zu definieren
    - Ausspielungen: [3.2](1-spielaufbau.html#3.2-linkobjekttyp); [5.9](1-spielaufbau.html#5.9-linkobjekttyp)

- Hinweisobjekt: [CP 4: Hinweisobjekt](#cp4-hinweisobjekt)
    - anzugeben, wenn bei Linkobjekttyp Option "Hinweisobjekt" eingestellt ist
    - Ausspielungen: [4.1](1-spielaufbau.html#4.1-media)

- Bild für Sammelalbum: Contentful Media Asset
    - Ausspielungen: [7.1](1-spielaufbau.html#7.1-bild-fuer-sammelalbum)

- World Maps: [Worldmap](#worldmap) (mult.)
    - Optional. Kann
    - Fürs Einrichten können mehrere Worldmaps eingetragen werden
    - Die jeweils oberste Worldmap wird im Spiel benutzt

- Hint Text: Text
    - Ausspielungen: [5.1](1-spielaufbau.html#5.1-hint-text)

- Hint Image: Contentful Media Asset
    - Ausspielungen: [5.1](1-spielaufbau.html#5.1-hint-text)


## CP3: Objekt

- Titel: Text
    - Ausspielungen: [5.6](1-spielaufbau.html#5.6-titel); [7.5](1-spielaufbau.html#7.5-titel)

- Media: Contentful Media Asset (mult.)
    - Ausspielungen: [7.4](1-spielaufbau.html#7.4-media)

- Objektspezifische Story: [Textobjekt](#textobjekt)
    - Ausspielungen: [5.7](1-spielaufbau.html#5.7-objektspezifische-story); [7.6](1-spielaufbau.html#7.6-objektspezifische-story)

- Stiftende Organisation: [CP5: Institution](#cp5-institution)

- Zum Teilen freigegeben: ja/nein
    - Ausspielungen: [7.7](1-spielaufbau.html#7.7-zum-teilen-freigegeben)

- Container Type: [Containertyp](#extension-containertyp)
    - muss mit Dateityp von Media korrespondieren

- Long Dimension: Fließkommazahl
    - gibt die Länge der langen Seite des darzustellenden 2D-Objekts in Metern an.
    - anwendbar auf Containertypen "Paper" und "Film"

- Fragmentation: [Fragmentzahl](#extension-fragmentzahl)
    - anwendbar auf Containertyp "Paper"

## CP4: Hinweisobjekt

Das Hinweisobjekt ist ein 2D-Objekt mit Vorder- und Rückseite, das frei bewegt werden kann.

- Media: Contentful Media Asset
    - vorgesehen sind zwei Bilddateien, die die Vorder- und Rückseite
    - Ausspielungen: [4.1](1-spielaufbau.html#4.1-media)

## CP5: Institution

- Titel: Text
    - Ausspielungen: [7.8](1-spielaufbau.html#7.8-titel)

- Logo: Contentful Media Asset
    - Ausspielungen: [7.9](1-spielaufbau.html#7.9-logo)

## Worldmap

- Title: Text

- Map File: Contentful Media Asset
    - Ausschließlich aus der [Portal Editor Companion App](TODO:LINK) exportierte .map Dateien hier eingetragen
    - Der nach Upload der Datei automatisch erzeugte Title-Eintrag des Contentful Media Assets (nicht des Wordmap Objekts) darf __nicht geändert__ werden


## Weitere Content-Modelle und Erweiterungen



### Textobjekt

### Extension Linkobjekttyp

- Optionen: Magischer Kompass, Pharus-Nadel, Hinweisobjekt
- legt den Typ des Navigationsartefakts fest, das zum nächsten Portal führt

### Extension Tour-Farbe

- 6 Farb-Optionen
- definiert Einfärbung verschiedener UI-Elemente, die sich durch die Nutzungserfahrung der Tour ziehen.

### Extension Containertyp

- Optionen und korrespondierende Media Dateitypen:
    - Self-contained: erfordert 3D-Datei mit zusätzlicher Vorschau-Bilddatei
    - Paper: erfordert Bilddatei
    - Picture Frame: erfordert Bilddatei
    - Camera on Tripod: erfordert Bilddatei
    - Gramophone: erfordert Audiodatei
    - Film: erfordert Videodatei
    - Slide Projector: erfordert Bilddatei. Projektionsfläche sollte an einer physischen Wand platziert werden
    - Slide Projector with Screen: erfordert Bilddatei. Mit zusätzlicher Leinwand für Fälle, wenn keine physische Wand zur Verfügung steht




### Extension Fragmentzahl

- Nur wirksam in Verbindung mit Containertyp "Paper"
- Gibt an, in wie vielen Einzelteilen das Objekt im Portal aufgefunden wird
- Optionen: None (keine Fragmentierung), 2, 3, 4
