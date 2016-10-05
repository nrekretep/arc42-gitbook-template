# Kontextabgrenzung

> __Form__
>
> * Diverse Kontextdiagramme (siehe folgende Abschnitte)
> * Listen von Nachbarsystemen mit deren Schnittstellen.


## Fachlicher Kontext {#functional-context}

> __Form__
>
> Logisches Kontextdiagramm, in der UML z.B. simuliert durch Klassendiagramme, Use Case > Diagramme,Kommunikationsdiagramme - kurz durch alle Diagramme, die das System als Black Boxdarstellen und die Schnittstellen zu den Nachbarsystemen (mehr oder weniger ausführlich)beschreiben.
>
> Alternativ oder ergänzend können Sie einfach eine Tabelle verwenden. Der Titel gibt den Namen Ihres Systems wieder; die drei Spalten sind: Nachbarsystem, Input, Output. Auch so kommen Sie zu einer kompletten Schnittstellenbeschreibung.

## Technischer- oder Verteilungskontext {#technical-context}

> __Form__
> z.B.: UML Deployment-Diagramm mit den Kanälen zu Nachbarsystemen, begleitet von einer > Mapping-Tabelle Kanal x Input/Output.****

## Externe Schnittstellen {#external-interfaces}

### Externe Schnittstelle 1

__Identifikation der Schnittstelle__

| Name / Bezeichnung der Schnittstelle | Version | Änderungen gegenüber Vorversion | Verantwortlicher Ansprechpartner / Rolle | Wer hat geändert und warum? |
| ------------------------------------ | ------- | ------------------------------- |---------------|-----------------------------|
| Name der Schnittstelle | | | | |

#### Fachlicher Kontext der Schnittstelle

__Fachliche Abläufe__

* Diagramm oder Beschreibung der fachlichen Abläufe

__Fachliche Bedeutung der Daten__
* Beschreibung der fachlichen Bedeutung* Technischer Kontext* Form der Interaktion

#### Anforderungen an die Schnittstelle

__Sicherheitsanforderungen__

__Mengengerüste__
* Laufzeit
* Durchsatz / Datenvolumen
* Verfügbarkeit
* Protokollierung
* Archivierung

#### Beteiligte Resourcen

__Syntax: Daten und Formate__
* Datenformate
* Gültigkeits- und Plausibilitätsregeln
* Codierung, Zeichensätze
* Konfigurationsdaten

__Syntax: Methoden/Funktionen__
* Prüfdaten

__Ablauf der Schnittstelle__
* fachliche oder technischer Ablauf

__Semantik__
* Nebenwirkungen, Konsequenzen

__Technische Infrastruktur__
* Technische Protokolle

__Fehler- und Ausnahmebehandlung__
* Welche Fehler werden erkannt?
* Wie werden sie intern behandelt?
* Welche Fehler werden nach aussen gegeben?

__Einschränkungen und Voraussetzungen__
* Berechtigungen
* Zeitliche Einschränkungen
* Parallele Benutzung
* Voraussetzungen zur Nutzung

#### Betrieb der Schnittstelle

__Metainformationen der Schnittstelle__
* Verantwortliche
* Kosten der Nutzung
* Organisatorisches
* Versionierung

__Beispiele für Nutzung und Daten__
* Beispieldaten
* Beispielabläufe / -interaktionen
* Programmierbeispiele
