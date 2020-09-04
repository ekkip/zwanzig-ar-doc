---
title: CMS
parent: Übersicht
has_children: true
nav_order: 2
---

# Content Management System

Die Spiel-App Object by Object wird befüllt über ein Content Management System (CMS).

Es wird die Headless-CMS-Lösung von [Contentful](https://www.contentful.com) verwendet, siehe [Einrichtungsanleitung](2.1-einrichtung.html)

## Content versus Media

In Contentful wird grundsätzlich zwischen Einträgen (Entries bzw. Content) und Mediendateien (Assets bzw. Media) unterschieden.

![Contentful Hauptmenü](/img/cms-1.png)

*Einträge sind im Contentful Projekt-Space über den Menüpunkt __Content__ zugänglich. Dies ist gleichzeitig der Haupteinstiegspunkt für die redaktionelle Betreuung. Mediendateien sind im Contentful Projekt-Space über den Menüpunkt __Media__ zugänglich.*


Die Einträge bilden die eigentliche [CMS-Struktur](2.2-cms-struktur.html) des Projektes ab.

![Contentful Entries](/img/cms-2.png)

*Einträge können hier nach Typ gefiltert und neu angelegt werden.*

## Veröffentlichungsstatus von Einträgen

![Contentful Entries](/img/cms-3.png)

*Der Veröffentlichungs-Status jedes Eintrags kann festgelegt werden.*

Da die __Object by Object__ App und in die __Portal Editor__ Companion App über unterschiedliche Schnittstellen auf das CMS zugreifen, sind die CSM-Einträge ja nach Veröffentlichungs-Status unterschiedlich sichtbar:

| Status    | Object by Object                      | Portal Editor |
| --------: | ----------------------------------:   | ------------: |
| Published | Sichtbar                              | Sichtbar      |
| Changed   | _Letzte gepublishte Version_ sichtbar | Sichtbar      |
| Draft     | __Nicht__ sichtbar                    | Sichtbar      |


## Haupt- und Zusatzinhalte

Das CMS enthält eine einheitliche Datenstruktur, in der zweierlei Inhalte gespeichert werden:

- Redaktionelle [Hauptinhalte](2.3-hauptinhalte.html)
- Spieltechnische [Zusatzinhalte](2.4-zusatzinhalte.html)
