---
title: CMS
parent: Übersicht
nav_order: 2
---

# CMS

Als CMS dient die Headless-CMS-Lösung von Contentful.

## CP0: Game

- Titel

- Geschichten: [CP 1: Geschichte](2-cms.html#cp1-geschichte) (mult.)


## CP1: Geschichte

- Titel

- Anmoderation: [Textobjekt](2-cms.html#textobjekt)
    - Ausspielungen: [2.2](#2.2-anmoderation); [6.3](#6.3-anmoderation)

- Abmoderation: [Textobjekt](2-cms.html#textobjekt)
    - Ausspielungen: Ende letzte AR-Session; [6.4](#6.4-abmoderation)

- Portale: [CP 2: Portal](2-cms.html#cp2-portal) (mult.)

- Einstiegs-Linkobjekttyp: [Linkobjekttyp](2-cms.html#extension-linkobjekttyp)
    - bei Option "Hinweisobjekt" ist zusätzlich ein Hinweisobjekt zu definieren
    - Ausspielungen: [2.3](#2.3-einstiegs-linkobjekttyp)

- Einstiegs-Hinweisobjekt: [CP 4: Hinweisobjekt](2-cms.html#cp4-hinweisobjekt)
    - anzugeben, wenn bei Einstiegs-Linkobjekttyp Option "Hinweisobjekt" eingestellt ist
    - Ausspielungen: [4.1](#4.1-media)

- Bild für Tourauswahl: Contentful Media
    - Ausspielungen: [1.1](#1.1-bild-fuer-tourauswahl); [6.1](#6.1-bild-fuer-tourauswahl)

- Text für Tourauswahl: Text
    - Ausspielungen: [1.3](#1.3-text-fuer-tourauswahl)

- Tourlänge: Zahl
    - ungefähre Angabe in Minuten
    - Ausspielungen: [1.4](#1.4-tourlaenge)

- Farbe: [Tour-Farbe](2-cms.html#extension-tour-farbe)


## CP2: Portal





## CP3: Objekt

## CP4: Hinweisobjekt

Das Hinweisobjekt ist ein 2D-Objekt mit Vorder- und Rückseite, die

- Media: Contentful Media
    - vorgesehen sind zwei Bilddateien, die die Vorder- und Rückseite
    - Ausspielungen: [4.1](#4.1-media)

## CP5: Institution




## Weitere Content-Modelle und Erweiterungen

### Textobjekt

### Extension Linkobjekttyp

- Optionen: Magischer Kompass, Pharus-Nadel, Hinweisobjekt
- legt den Typ des Navigationsartefakts fest, das zum nächsten Portal führt

### Extension Tour-Farbe

- 6 Farb-Optionen
- definiert Einfärbung verschiedener UI-Elemente, die sich durch die Nutzungserfahrung der Tour ziehen.
