---
Thema: SLA - Service Level Agreement
Präsentatoren: Lars, Kevin, Gabriel, Peter
Datum: 07.10.2025
Quellverzeichnis: "[[Ausarbeitung]]"
TO-DO: "[[TO-DO]]"
---
## <u>Verhandlungsgespräch</u>
[Aufführung](Verhandlungsgespräch.md)
Damit erstmal Wilkommen auch zu unserer Präsentation. Person 1 und Person 2 haben ja unser Thema angedeutet und schon ein wenig beleuchtet. Unser Thema ist SLA.

## <u>Definition</u>
<!-- Quell-ID 1 -->
SLA ist die Abkürzung für *Service Level Agreement* und behandelt einen auszuführenden Service mit dem zu erfüllenden Leistungsniveau zwischen 2 Verhandlungspartnern. Es ist also eine vertragliche Vereinbarung. Dabei ist er sowohl zwischen einem Anbieter und einem externen Kunden vereinbar als auch intern in einem Unternehmen zwischen Abteilungen und/oder Teams.

> In meinerm Unternehmen ist es bspw. ersteres

## <u>Vorteile</u>
<!-- Quell-ID 2 -->
Und warum macht man das jetzt genau?

Zum einen verbessert man so die Servicequalität. "Der Support soll halt schnell reagieren". "Wir bemühen uns um eine hohe Uptime". Klingt jetzt nicht wirklich motivierend. Mit SLAs hat man die Möglichkeit, eigene Produkte und den eigenen 
Service besser analysieren zu können. Durch die eingebauten Mechanismen und Verpflichtungen durch klare Ziele, Konsequenzen bei Nichteinhaltung, monatliche Berichte etc stellt man fest, was funktioniert und was Potenzial zur Verbesserung hat.
So wird anfängliche Satz zu: "Reaktionszeit < 1 Stunde, Lösungszeit < 4 Stunden.“ Das suggeriert Professionalität. "Wir haben unsere Prozesse so im Griff, dass wir sie vertraglich garantieren können". Fantastisch.

Jetzt stellt euch vor, ihr habt ein dringliches Problem und fragt euch, wo genau ihr euch melden sollt. Als einzige Antwort habt ihr "Rufen sie einfach wen an, es wird schon jemand abnehmen" erhalten. Puuuhh.
Durch klare Rollenverteilung und festgelegte Verantwortlichen wird Klarheit geschaffen über die Prozesse und Kanäle für die Behebung von Problemen. Das erleichtert die Kommunikation ungemein. Eine Aussage wie „Sie erreichen uns auf der Support-Hotline 24/7 bei folgenden Problemen“ klingt doch hilfreicher.

Auch werden die Risiken minimiert, indem man proaktiv vorangehen kann. Punkt Risikomanagement. Der Prozess identifiziert potenzielle Risiken, begrenzt  und kompensiert diese, bevor sie zu teuer oder rechtlich problematisch werden. Eine ständiges Monitoring (sprich Überwachung) ist dabei unabdingbar. Ein SLA ist also nicht nur ein reagierendes Kontrollinstrument, sondern ein aktives Werkzeug des Risikomanagements. 

Zu guter Letzt definieren wir die Erwartungen in Bezug auf die Service-Verfügbarkeit, legen Richtlinien für Ausfallzeiten fest und bestimmen die Verfahren für Ausfälle und die Notfallwiederherstellung. Diese Maßnahmen tragen dazu bei, Störungen und unerwartete Ausfallzeiten zu minimieren und technische Probleme und Service-Ausfälle schnell zu beheben.

Ich denke, das macht es klar, warum man unbedingt ein SLA Vertrag abschließen möchte. Kleiner Fun-Fact, die Verträge können ziemlich groß werden. Der 
Microsoft Azure SLA Vertrag, aus dem wir später auch noch einen Auszug zeigen werden, ist über 100 Seiten lang.

## <u>Arten von SLA</u>
<!-- Quell-ID 3 -->
![[SLA_Arten.png]]
<!-- Quell-ID 4 -->
Aber es gibt nicht nur den einen SLA Vertrag. Tatsächlich werden SLAs in 3 bzw 4 Arten unterteilt. Alle haben ähnliche Ziele, dienen aber jeweils unterschiedlichen Geschäftsbeziehungen und enthalten individuelle Nuancen.

Das klassische SLA - oder jedenfalls das, was ich mir unter SLA immer vorstelle - ist das kundenspezifische SLA. Also der Vertrag zwischen Kunde und Anbieter. Dabei werden hier individuelle Anpassungen ausgehandelt.
Wenn ein Kunde beispielsweise die Dienste eines Internetanbieters abonniert, schließt er/sie eine SLA-Vereinbarung ab, die ihm/Ihr ein bestimmtes Maß an Internetgeschwindigkeit, Betriebszeit und technischer Unterstützung garantiert.

Kundenspezifische SLAs gehen oftmals mit einer hohen Kundenzufriedenheit einher, da sie maßgeschneiderte Vereinbarungen haben und klare Strukturen haben, erfordert habe einen hohen Verwaltungsaufwand.

Im Gegensatz zu den individuellen SLAs stehen die servicebasierten SLAs. 
Hier wird eine übergreifende SLA für alle Kunden, die die gleiche Dienstleistung benutzen, erstellt. Es gibt klare Standards und ermöglicht eine einfache Verwaltung. Kunden, mit besonderen Anforderungen können hier aber nicht berücksichtigt werden.
Eine Mischung aus beidem kann Abhilfe schaffen.

Und das berücksichtigt die Mehrstufige (Multi-Layer) SLA. Ein Konzern nutzt ein allgemeines SLA auf Unternehmensebene für alle Kunden gleichermaßen, die aber mit weiteren individuellen Verinbarungen je nach Kunde beschmückt sind.
Ein Telekommunikationsunternehmen kann zum Beispiel allen seinen Kunden grundlegende Dienste und Unterstützung anbieten, aber mehrere Preisspannen haben, die das Serviceniveau für jede Kundengruppe bestimmen.
Das gibt uns hohe Flexibilität und eine gute Balance zwischen Standardisierung und Individualisierung. Erfordert aber natürlich einen komplexe Verwaltung und ein gutes SLA-Managment.

Zu guter Letzt gibt es auch interne SLAs, die die Verantwortlichkeiten zwischen Teams und Abteilungen klären. Ziemlich straight forward. Trotzdem muss ich hier etwas hinzufügen:
es gibt hier nämlich unterschiedliche Auffassungen. Da SLAs per se nur das Verhältnis zwischen Diensleister und Kunden klären und nicht zwischen internen Organisationen, sind interne "SLAs" eher OLAs - also Operational Level Agreement. Die funktionieren im Kern aber genauso. Wir haben uns trotzdem dazu entschieden, das mitreinzunehmen, um euch zu zeigen, dass es so etwas auch intern gibt. Wir werden aber nicht weiter auf OLAs eingehen.
## <u>Komponenten von SLAs</u>
<!-- Quell-ID 5 -->
Einige Komponenten wurden anfangs in unserem [[Verhandlungsgespräch]] vorgestellt. Wir haben bspw. darüber geredet, welchen Standard wie anstreben: eine Verfügbarkeit von 99,5%.. Die Leistungsverfolgung ist ein essentieller Punkt im SLA. 
Wir haben die eine Vertragsstrafe angesprochen: eine 10%-ige Kürzung der Monatsgebühr bei Nichteinhaltung der 10min Frist bei einer Störung. Ohne Wiedergutmachung kein SLA.
Zu guter Letzt haben wir uns noch darauf geeinigt, dass wir einen monatlichen Bericht über unseren Service bereitstellen und zu unserem Vertragspartner schicken. Verständlicherweise wollen diejenigen, die den Service in Anspruch nehmen, auch eine aufgeschlüsselte Berichterstattung haben.
Das waren aber natürlich längst nicht alle Punkte. Und man muss dazu sagen, die Inhalte eines SLA sind je nach Anwendungsfall unterschiedlich und können in ihrem Umfang und ihren Schwerpunkte schwanken. Dennoch gibt es Ähnlichkeiten und Komponenten, die einfach unverzichtbar sind. Neben unseren genannten zählen dazu:

* einen Überblick. Die Vorstellung grundlegender Merkmale des Vertrages wie der grobe Überblick über die zu erbringenden Dienstleistungen, die Laufzeit und die Vertragspartner.
* Die Beschreibung der Dienstleistung nochmal spezifisch mit Informationen über die Erbringung der Leistung, Abwicklungszeiten, Wartungspläne etc. Am Ende sollten keine Fragen mehr über die Dienstleistungen da sein.
* EIne Aufschlüsselung der Stakeholder mit einer Aufführung der Zuständigkeiten, Kontaktmöglichkeiten und Rollen der Parteien.

Und noch einige weitere, die wir jetzt hier nur einblenden werden
* Ausschlüsse
* Sicherheitsprotokolle
* Entschädigungsklausel
* Prozess zur Überprüfung und Anpassung
* Kündigungsprozess und Bedingungen
* Unterschriften

## Auszug aus einem SLA Vertrag - Musterbeispiel
<!-- Quell-ID 6 -->
[![[SLA_Ausschnitt.png|200]]](SLA_Auschsnitt.png)

*Auszug aus einem SLA Vertrag*
Um euch das auch anhand eines Beispiels zu zeigen, haben wir hier einen Auszug aus der Microsoft Azure SLA für euch. Jeder, der sich bis jetztgefragt hat, wie so ein Vertrag aussieht, ich kann euch versichern, es ist nichts wildes.
Das Beispiel hier ist eine Übersicht über den Supportumfang und die Reaktionszeiten bei Supportanfragen, also im Grunde SLA-Regeln für Supportfälle.
Wir haben oben eine Beschreibung, welche Leistungen abgedeckt sind. Allgemeine Verfügbarkeit, technische Unterstüzung und Supportkanäle.
Daunter befinden sich die festgelegten Antwortzeiten, die nach Eingang des Tickets eingehalten werden müssen, da ansonsten Konsequenzen gezogen werden. Dabei werden hier unterschiedliche Schweregrade angegeben mit jeweils unterschiedlichen Bearbeitungszeiten.
* Schweregrad A für eine kritische Beeinträchtigung des Geschäftsbetriebs. Die Antwortzeit beträgt hier unter einer Stunde
* Schweregrad B für deutliche, aber nicht kritische Einschränkungen. Die Antwortzeit beträgt hier unter 2 Stunden
* Schweregrad C für geringfügige Auswirkungen mit einer Antwortzeit von unter 8 bzw 4 Stunden, je nach Supportplan
Darüber hinaus gibt es aber auch Verpflichtungen des Kundens, die erfüllt werden müssen wie bspw ein ständiger Austausch bis zur Problemlösung. Bei Nichteinhalltung, kann der Schwerefall heruntergesetzt werden.

```
IGNORIEREN
==========

Um euch das auch anhand eines Beispiels zu zeigen, haben wir hier ein Auszug aus einem Muster-SLA für euch.
Jeder, der sich bis jetztgefragt hat, wie so ein Vertrag aussieht, ich kann euch versichern, es ist nichts wildes. Das Beispiel zeigt den Abschnitt **Bereich des Agreements**, also welche konkreten Services unter diesen SLA fallen. Jetzt denken wir nochmal zurück zu den Komponenten und wissen, es geht um die **Beschreibung der Diensleistungen** - hier unterteilt in 2 Bereiche:
* Automatische Dienstleistungen gemäß SLA
	In diesem Teil wird geregelt, was automatisch passiert, wenn ein Problem an den Provider übergeben wird.
	- Dazu zählt der Punkt **Korrigierender Systemunterhalt:** Die Fehleranalyse und -behebung (Root-Cause-Analyse, Bug Fixing) und die
	- **Statusaktualisierung**, bei der laufend Information an den Kunden über den Ticketstatus über eSupport oder ähnliche Systeme weitergegben wird
* Der zweite Bereich sind weitere Supportanfragen, die durch das SLA abgedeckt sind
	Hier wird festgelegt, welche zusätzlichen Services mit dem SLA abgedeckt sind – also was der Kunde erwarten kann. Dazu zählt bspw.
	- Applikation überwachen
	- Erweiterung bestehender Software und
	- Level-2-Support:
Wie ihr seht, alles ziemlich trocken und informativ - wie ein Vertrag eben so ist.

==========
IGNORIEREN
```