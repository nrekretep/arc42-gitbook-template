# Randbedingungen {#constraint}
*(engl.: Architecture Constraints)*

__Inhalt__

Fesseln, die Software-Architekten in ihren Freiheiten bezüglich des Entwurfs oder des Entwicklungsprozesses einschränken.

__Motivation__

Architekten sollten klar wissen, wo Ihre Freiheitsgrade bezüglich Entwurfsentscheidungen liegen und wo sie Randbedingungen beachten müssen.Randbedingungen können vielleicht noch verhandelt werden, zunächst sind sie aber da.

__Form__

Informelle Listen, gegliedert nach den Unterpunkten dieses Kapitels.

__Beispiele__

siehe Unterkapitel

__Hintergründe__

Im Idealfall sind Randbedingungen durch die Anforderungen vorgegeben, spätestens die Architekten müssen sich dieser Randbedingungen bewusst sein.

Den Einfluss von Randbedingungen auf Software- und Systemarchitekturen beschreibt [Hofmeister+1999] (Software-Architecture, A Practical Guide, Addison-Wesley 1999) unter dem Stichwort „Global Analysis“.

## Technische Randbedingungen {#technical}

__Inhalt__
Tragen Sie hier alle technischen Randbedingungen ein.Zu dieser Kategorie gehören Hard- und Software-Infrastruktur,eingesetzte Technologien (Betriebssysteme, Middleware, Datenbanken, Programmiersprachen, ...).

### Technische Randbedingungen

* Hardware-Vorgabe
  * _Randbedingung 1_
  * _Randbedingung 2_
* Software-Vorgaben
  * _Randbedingung i_
* Vorgaben des Systembetriebs
  * _Randbedingung j_
* Programmiervorgaben
  * _Randbedingung k_

__Beispiele__
 
| Randbedingung | Erläuterung |
| ------------- | ----------- |
| Hardware-Infrastruktur | Prozessoren, Speicher, Netzwerke, Firewalls und andere relevante Elemente der Hardware- Infrastruktur|
| Software-Infrastruktur | Betriebssysteme, Datenbanksysteme, Middleware, Kommunikationssysteme, Transaktionsmonitor, Webserver, Verzeichnisdienste|
| Systembetrieb | Batch- oder Onlinebetrieb des Systems oder notwendiger externer Systeme?|
| Verfügbarkeit der Laufzeitumgebung | Rechenzentrum mit 7x24h Betriebszeit? Gibt es Wartungs- oder Backupzeiten mit eingeschränkter Verfügbarkeit des Systems oder wichtiger Systemteile?|
| Grafische Oberfläche |Existieren Vorgaben hinsichtlich grafischer Oberfläche (Style Guide)?|
| Bibliotheken, Frameworks und Komponenten | Sollen bestimmte „Software-Fertigteile“ eingesetzt werden?|
| Programmiersprachen | Objektorientierte, strukturierte, deklarative oder Regelsprachen, kompilierte oder interpretierte Sprachen?|
| Referenzarchitekturen |Gibt es in der Organisation vergleichbare oder übertragbare Referenzprojekte?|
| Analyse- und Entwurfsmethoden |Objektorientierte oder strukturierte Methoden?|
| Datenstrukturen |Vorgaben für bestimmte Datenstrukturen, Schnittstellen zu bestehenden Datenbanken oder Dateien|
| Programmierschnittstellen |Schnittstellen zu bestehenden Programmen|
| Programmiervorgaben |Programmierkonventionen, fester Programmaufbau |
| Technische Kommunikation |Synchron oder asynchron, Protokolle|
| Betriebssystem und Middleware | Vorgegebene Betriebssysteme oder Middleware|


## Organisatorische Randbedingungen {#organisation}

__Inhalt__

Tragen Sie hier alle organisatorischen, strukturellen und ressourcenbezogenen Randbedingungen ein. Zu dieser Kategorie gehören auch Standards, die Sie einhalten müssen und juristische Randbedingungen.

### Organisation und Struktur
_hier Randbedingungen einfügen_

### Ressourcen (Budget, Zeit, Personal)
_hier Randbedingungen einfügen_

### Organisatorische Standards
_hier Randbedingungen einfügen_

### Juristische Faktoren

_hier Randbedingungen einfügen_

__Beispiele__

__Organisation und Struktur__

| *Randbedingung* | *Erläuterung* |
| --------------- | ------------- |
| Organisationsstruktur beim Auftraggeber| Droht Änderung von  Verantwortlichkeiten? +Änderung von Ansprechpartnern |
| Organisationsstruktur des Projektteams | mit/ohne Unterauftragnehmer + Entscheidungsbefugnis der Projektleiterin |
| Entscheidungsträger | Erfahrung mit ähnlichen Projekten +Risiko-/Innovationsfreude |
| Bestehende Partnerschaften oder Kooperationen | Hat die Organisation bestehende Kooperationen mit bestimmten Softwareherstellern? +Solche Partnerschaften geben oftmals Produktentscheidungen (unabhängig von Systemanforderungen)vor.
| Eigenentwicklung oder externe Vergabe | Selbst entwickeln oder an externe Dienstleister vergeben? (_Make or buy_) |
| Entwicklung als Produkt oder zur eigenen Nutzung? | Bedingt andere Prozesse bei Anforderungsanalyse und Entscheidungen.Im Fall der Produktentwicklung: * Neues Produkt für neuen Markt? * Verbessertes Produkt für bestehenden Markt? * Vermarktung eines bestehenden (eigenen) Systems * Entwicklung ausschließlich zur eigenen Nutzung? |

__Ressourcen (Budget, Zeit, Personal)__


| *Randbedingung* | *Erläuterung* |
| --------------- | ------------- |
| Festpreis oder Zeit/Aufwand? | Festpreisprojekt oder Abrechnung nach Zeit und Aufwand? |
| Zeitplan | Wie flexibel ist der Zeitplan? Gibt es einen festen Endtermin? Welche Stakeholder bestimmen den Endtermin? |
| Zeitplan und Funktionsumfang  |Was ist höher priorisiert, der Termin oder der Funktionsumfang? |
| Release-Plan | Zu welchen Zeitpunkten soll welcher Funktionsumfang in Releases/Versionen zur Verfügung stehen? |
| Projektbudget | Fest oder variabel? In welcher Höhe verfügbar? |
| Budget für technische Ressourcen | Kauf oder Miete von Entwicklungswerkzeugen +(Hardware und Software)? |
| Team | Anzahl der Mitarbeiter und deren Qualifikation, Motivation und kontinuierliche Verfügbarkeit. |

__Organisatorische Standards__

| *Randbedingung* | *Erläuterung* |
| --------------- | ------------- |
| Vorgehensmodell | Vorgaben bezüglich Vorgehensmodell? Hierzu gehören auch interne Standards zu Modellierung, Dokumentation und Implementierung. |
| Qualitätsstandards | Fällt die Organisation oder das System in den Geltungsbereich von Qualitätsnormen (wie ISO-9000)? |
| Entwicklungswerkzeuge | Vorgaben bezüglich der Entwicklungswerkzeuge (etwa: CASE-Tool, Datenbank, Integrierte Entwicklungsumgebung,Kommunikationssoftware, Middleware, Transaktionsmonitor). |
| Konfigurations- und Versionsverwaltung | Vorgaben bezüglich Prozessen und Werkzeugen |
|Testwerkzeuge und -prozesse|Vorgaben bezüglich Prozessen und Werkzeugen |
| Abnahme- und Freigabeprozesse | Datenmodellierung und Datenbankdesign +Benutzeroberflächen +Geschäftsprozesse (Workflow) +Nutzung externer Systeme (etwa: schreibender Zugriff bei externen Datenbanken) |
| Service Level Agreements | Gibt es Vorgaben oder Standards hinsichtlich Verfügbarkeiten oder einzuhaltender Service-Levels? |

__Juristische Faktoren__

| *Randbedingung* | *Erläuterung* |
| --------------- | ------------- |
| Haftungsfragen| Hat die Nutzung oder der Betrieb des Systems mögliche rechtliche Konsequenzen? +Kann das System Auswirkung auf Menschenleben oder Gesundheit besitzen? +Kann das System Auswirkungen auf  Funktionsfähigkeit externer Systeme oder Unternehmen besitzen? |
| Datenschutz | Speichert oder bearbeitet das System „schutzwürdige“ Daten? |
| Nachweispflichten | Bestehen für bestimmte Systemaspekte juristische Nachweispflichten? |
| Internationale Rechtsfragen | Wird das System international eingesetzt? +Gelten in anderen Ländern eventuell andere juristische Rahmenbedingungen für den Einsatz (Beispiel: Nutzung von Verschlüsselungsverfahren)? |

## Konventionen

__ Inhalt__

Fassen Sie unter dieser Überschrift alle Konventionen zusammen, die für die Entwicklung der Software-Architektur relevant sind.

__Form__

Entweder die Konventionen als Kapitel hier direkt einhängen oder aber auf entsprechende Dokumente verweisen.

__Beispiele__
* Programmierrichtlinien
* Dokumentationsrichtlinien
* Richtlinien für Versions- und Konfigurationsmanagement
* Namenskonventionen
