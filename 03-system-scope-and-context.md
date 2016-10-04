# Kontextabgrenzung

__Inhalt__

Die Kontextsicht grenzt das System, für das Sie die Architektur entwickeln, von allen Nachbarsystemen ab. Sie legt damit die wesentlichen externen Schnittstellen fest.Stellen Sie sicher, dass die Schnittstellen mit allen relevanten Aspekten (was wird übertragen, in welchem Format wird übertragen, welches Medium wird verwendet, ...) spezifiziert wird, auch wenn einige populäre Diagramme (wie z.B. das UML Use-Case Diagramm) nur ausgewählte Aspekte der Schnittstelle darstellen.

__Motivation__

Die Schnittstellen zu Nachbarsystemen gehören zu den kritischsten Aspekten eines Projektes. Stellen Sie rechtzeitig sicher, dass Sie diese komplett verstanden haben.

__Form__

* Diverse Kontextdiagramme (siehe folgende Abschnitte)
* Listen von Nachbarsystemen mit deren Schnittstellen.

Die folgenden Unterkapitel zeigen die Einbettung unseres Systems in seine Umgebung.

## Fachlicher Kontext {#functional-context}

__Inhalt__

Festlegung aller footnote:[alle,Zwar sind wir an vielen Stellen zu Pragmatismus bereit – hierjedoch bestehen wir auf der vollständigen Auflistung aller *(a-l-l-e-r)* Nachbarsysteme.Zu viele Projekte sind daran gescheitert, dass sie ihre Nachbarn nicht kannten :-(]Nachbarsysteme des betrachteten Systems mit Spezifikation allerfachlichen Daten, die mit diesen ausgetauscht werden. Zusätzlich evtl. Datenformateund Protokolle der Kommunikation mit Nachbarsystemen und der Umwelt(falls diese nicht erst bei den spezifischen Bausteinen präzisiert wird.

__Motivation__

Verstehen, welche (logischen) Informationen mit Nachbarsystemen (in welcher Form)ausgetauscht werden.

__Form__

Logisches Kontextdiagramm, in der UML z.B. simuliert durch Klassendiagramme, Use Case Diagramme,Kommunikationsdiagramme - kurz durch alle Diagramme, die das System als Black Boxdarstellen und die Schnittstellen zu den Nachbarsystemen (mehr oder weniger ausführlich)beschreiben.

Alternativ oder ergänzend können Sie einfach eine Tabelle verwenden. Der Titel gibt den Namen Ihres Systems wieder; die drei Spalten sind: Nachbarsystem, Input, Output. Auch so kommen Sie zu einer kompletten Schnittstellenbeschreibung.

## Technischer- oder Verteilungskontext {#technical-context}

__Inhalt__
Festlegung der Kanäle zwischen Ihrem System, den Nachbarsystemen und der Umwelt;Zusätzlich eine Mapping-Tabelle, welcher logische Input (aus 3.1) über welchen Kanal ein- oder ausgegeben wird.

__Motivation__
Verstehen, über welche Medien Informationen mit Nachbarsystemen bzw. der Umwelt ausgetauscht werden.

__Form__
z.B.: UML Deployment-Diagramm mit den Kanälen zu Nachbarsystemen, begleitet von einer Mapping-Tabelle Kanal x Input/Output.****

## Externe Schnittstellen {#external-interfaces}

__Inhalt__

Spezifikation der Kommunikationskanäle, die ihr System mit den Nachbar-Systemen und der Umwelt verbinden.

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
