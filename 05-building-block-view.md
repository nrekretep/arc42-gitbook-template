# Bausteinsicht

> __Form__
> 
> Die Bausteinsicht ist eine hierarchische Sammlung von Blackbox- und Whitebox- Beschreibungen (siehe Abbildung unten):

> **Ebene 1** ist die Whitebox-Beschreibung des Gesamtsystems (System under Development / SUD) mit den Blackbox- Beschreibungen der Bausteine des Gesamtsystems
>
> **Ebene 2** zoomt dann in einige Bausteine der Ebene 1 hinein.Sie enthält somit alle vorhandenen Whitebox-Beschreibungen von Bausteinender Ebene 1, zusammen mit den Blackbox-Beschreibungen der Bausteine von Ebene 2.
>
> **Ebene 3** zoomt in einige Bausteine der Ebene 2 hinein, usw.
>
> __Whitebox-Template__
> Enthält mehrere Bausteine (== Blackboxes),zu denen Sie jeweils eine Blackbox Beschreibung erstellen können.
> 
> __Blackbox-Template (Kurzfassung)__
> Für jeden Baustein aus dem White-Box-Template können Sie folgende Angaben machen: (Kopieren Sie diese Punkte in die folgenden Unterkapitel)
> 
> ----

!INCLUDE "template-blackbox-short.md"

(eine ausführlichere Fassung des Blackbox-Templates finden Sie weiter unten.)

## Whitebox Gesamtsystem (Ebene 1)

> An dieser Stelle beschreiben Sie die Whitebox-Sicht der Ebene 1 gemäß dem Whitebox-Template.
> 
> Das Überblicksbild zeigt das Innenleben des Gesamtsystemsmit den darin enthaltenen Bausteinen 1 .. n,sowie deren Zusammenhänge und Abhängigkeiten.
> 
> Begründen Sie die Struktur: Warum gibt es diese Bausteine mitdiesen Abhängigkeiten/Schnittstellen.
> 
> Erklären Sie ggfs. auch verworfene Alternativen,mitsamt Begründung, warum sie verworfen wurden.
>
> ----

!INCLUDE "template-whitebox.md"

### _Baustein 1_ (Blackbox)

Beschreiben Sie diesen Baustein anhand des Blackbox-Templates.Nachfolgend finden Sie eine kompakte und eine ausführliche Fassung davon.

----

!INCLUDE "template-blackbox-short.md"

----

----

!INCLUDE "template-blackbox-long.md"

----

*(In den folgenden Abschnitten finden Sie nur noch die Kurzfassung des Blackbox-Template)*

### _Baustein 2_ (Blackbox)

!INCLUDE "template-blackbox-short.md"

### _Baustein n_ (Blackbox)

!INCLUDE "template-blackbox-short.md"

### Ebene 2

*An dieser Stelle können Sie den inneren Aufbau(einiger) Bausteine aus Ebene 1 als Whitebox beschreiben.*

#### _Baustein 1_ (Whitebox)

* ...zeigt das Innenleben von _Baustein 1_ in Diagrammform mit den lokalen Bausteinen 1.1 - 1.n,sowie deren Zusammenhänge und Abhängigkeiten.* begründet diese Struktur****

include::template-whitebox.adoc[]

===== _Baustein 1.1_ (Blackbox)

include::template-blackbox-short.adoc[]

===== _Baustein 1.2_ (Blackbox)

include::template-blackbox-short.adoc[]

===== _Baustein 1.n_ (Blackbox)

include::template-blackbox-short.adoc[]

==== _Baustein 2_ (Whitebox)

[role="arc42help"]***** ...zeigt das Innenleben von _Baustein 2_ in Diagrammformmit den lokalen Bausteinen 2.1 - 2.n,sowie deren Zusammenhänge und Abhängigkeiten.* begründet diese Struktur****

include::template-whitebox.adoc[]

===== _Baustein 2.1_ (Blackbox)

include::template-blackbox-short.adoc[]

===== _Baustein 2.2_ (Blackbox)

include::template-blackbox-short.adoc[]

===== _Baustein 2.n_ (Blackbox)

include::template-blackbox-short.adoc[]

==== _Baustein 3_ (Whitebox)

[role="arc42help"]***** ...zeigt das Innenleben von _Baustein 3_ in Diagrammformmit den lokalen Bausteinen 3.1 - 3.n,sowie deren Zusammenhänge und Abhängigkeiten.* begründet diese Struktur****

_<Hier Whitebox-Erläuterung für Baustein 3 einfügen>_

===== _Baustein 3.1_ (Blackbox)

include::template-blackbox-short.adoc[]

===== _Baustein 3.2_ (Blackbox)

include::template-blackbox-short.adoc[]

===== _Baustein 3.n_ (Blackbox)

include::template-blackbox-short.adoc[]

=== Ebene 3

[role="arc42help"]****An dieser Stelle können Sie den inneren Aufbau(einiger) Bausteine aus Ebene 2 als Whitebox beschreiben.****

[role="arc42help"]****Welche Bausteine Ihres Systems Sie hier beschreiben, müssen Sieselbst entscheiden. Bitte stellen Sie dabei Relevanz vor Vollständigkeit.Skizzieren Sie wichtige, überraschende, riskante, komplexe oder besondersvolatile Bausteine. Normale, einfache oder standardisierte Teile solltenSie weglassen.****

==== _Baustein 1.1_ (Whitebox)

[role="arc42help"]***** ...zeigt das Innenleben von _Baustein 1.1_ in Diagrammformmit den lokalen Bausteinen 1.1.1 - 1.1.n,sowie deren Zusammenhänge und Abhängigkeiten.* begründet diese Struktur****

include::template-whitebox.adoc[]

===== _Baustein 1.1.1_ (Blackbox)

include::template-blackbox-short.adoc[]

===== _Baustein 1.1.2_ (Blackbox)

include::template-blackbox-short.adoc[]
