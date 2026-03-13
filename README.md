# Benutzerschnittstelle (JavaScript, CSS)

## Höhendaten

Dieser Webservice bietet Zugriff auf hochpräzise Digitale Geländemodelle (DGM1) der deutschen Landesvermessungsämter. Die Anwendung ermöglicht die browserbasierte Analyse und Visualisierung topografischer Daten für Fachanwendungen und allgemeine Zwecke.

## Genauigkeit der Daten

| Art   | Typ des Geländes                      | Genauigkeit |
|-------|---------------------------------------|-------------|
| Höhe  | Flachland oder offenes Gelände        | ≤ ±15 cm    |
| Höhe  | Steiles Gelände oder dicht bewaldetes Gebiet | ≤ ±30 cm    |
| Lage  |                                       | ≤ ±30 cm    |

## Funktionsumfang

### Topografische Analyse
* **Punktabfrage:** Interaktive Ermittlung präziser Höhenwerte.
* **Profilmessung:** Distanz- und Höhenberechnung zwischen zwei Punkten inklusive Steigungs- und Winkelangaben.
* **Geländeparameter:** Berechnung von Hangneigung (Slope), Hangexposition (Aspect) und Geländerauheit (Roughness).
* **Indizes:** Generierung von Topographic Position Index (TPI) und Terrain Ruggedness Index (TRI).

### Visualisierung & Kartografie
* **Reliefdarstellung:** Dynamische Erzeugung von Schattierungen (Hillshade) und Farbreliefs.
* **Höhenlinien:** Parametrisierbare Generierung von Vektor-Höhenschichtlinien.
* **Ebenensteuerung:** Individuelle Anpassung von Farbschemata, Mischmodi (Blend Modes) und Bildfiltern (Helligkeit, Kontrast, Sättigung).
* **Layer-Management:** Flexible Sortierung und Transparenzsteuerung der Analyseebenen.

### Datenmanagement & Werkzeuge
* **Import/Export:** Unterstützung von GPX, KML und GeoJSON.
* **Speichersystem:** Lokale Persistenz von Daten und Einstellungen via OPFS (Origin Private File System) und IndexedDB.
* **Bereichsfunktionen:** Automatisierter Abruf von Kachel-Paketen über definierte Rechtecke.

## Nutzung
Der Zugriff erfolgt interaktiv über die Weboberfläche (oder automatisiert über die bereitgestellte API).

[Höhendaten für Deutschland](https://hoehendaten.de/)
