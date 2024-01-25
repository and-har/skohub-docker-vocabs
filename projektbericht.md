# **Publikation eines kontrollierten Vokabulars mit SkoHub Vocabs**
## **Projektbericht im Modul MALIS 23.2 IT2 - Dozent: Adrian Pohl**
### **Aufgabe: Kleines Projekt IT2**

vorgelegt von: **Andreas Hartmann** und **Benjamin Heu**


## Inhaltsübersicht
- [1. Beschreibung des gewählten Vokabulars](#1)
- [2. Zusammenarbeit auf GitHub und an der Turtel-Datei](#2)
- [3. Probleme beim Einrichten des Repositoriums](#3)
- [4. Verständnis von RDF und SKOS vor und nach Bearbeitung](#4)
- [5. Ausblick auf weitere Nutzungs- und Anwendungsfälle](#5)

<a id="1"></a>
## **1. Beschreibung des gewählten Vokabulars**

Das gewählte Vokabular wird im _Bundesamt für Migration und Flüchtlinge_ in der Literaturdokumentation zur Klassifikation von Deskriptoren verwendet. Die einzelnen Deskriptoren werden je nach inhaltlicher Entsprechung einer oder mehreren Systemstellen der Systematik zugeordnet. Auf diese Weise kann eine bestehende Sinnverwandtschaft von Deskriptoren abgebildet werden, die je nach Zuordnung zu einer Systemstelle inhaltlich einen anderen Bedeutungskontext haben können. So ist etwa der Deskriptor "_Sicherheitsbehörde_" sowohl der Systemstelle 4.35 für "_Öffentliche Verwaltung, staatliche Gliederung_" als auch 4.51 für "_Polizei und nichtmilitärische Sicherheitsorgane_" zugeordnet. Die Systematik dient in erster Linie somit der klassifikatorischen Erschließung von Deskriptoren.

Inhaltlich basiert die Systematik teilweise auf der _EMN Glossary on Asylum and Migration Classification_ und wurde für die Literaturdokumentation des Bundesamtes um weitere Hauptgruppen erweitert. Aktuell besteht sie aus insgesamt 11 Hauptgruppen und 205 Systemstellen, von denen im Rahmen dieses Projektes die Hauptgruppe 4.00 „_Politik und Sicherheitsfragen_“ mit ihren Untergruppen ausgewählt und zunächst in die Englische Sprache übersetzt wurden. Die Hauptgruppe 4.00 umfasst insgesamt acht Teilgruppen (4.10 bis 4.80), von denen die Gruppen 4.30 bis 4.60 wiederum weitere Untergruppen enthalten. Daraus ergeben sich insgesamt 27 Systemstellen, die im Rahmen des Projektes bearbeitet und als SKOS-Konzepte angelegt wurden.

Bisher existiert keine geeignete Software zur Verwaltung und Pflege der Thesaurus-Systematik. Außerdem ist ein Export der Systematik in ein anderes System bisher nicht möglich, da sie in keinem Austauschformat vorliegt, dass eine maschinelle Nachnutzung ermöglicht. Die Datengrundlage ist lediglich ein PDF-Dokument. Die Übertragung der Thesaurus-Systematik in das SKOS-Format ist daher ein erster wichtiger Schritt für die Pflege, den Datenaustausch und -export sowie das Anlegen von Crosskonkordanzen zu anderen Systematiken.

![eb90707a-e174-44ad-a19c-9254c062e5ec](https://github.com/and-har/thesaurus_systematik/assets/148260522/9b1c419d-9c3c-47bd-9c9d-59419eb346d9)
_Abb. 1: Ausschnitt aus dem PDF-Dokument_

<a name="2"></a>
## **2. Zusammenarbeit auf GitHub und an der Turtel-Datei**

Grundsätzlich war das Vorgehen vor allem in der Anfangsphase durch agile Elemente geprägt. Die Zusammenarbeit auf der Plattform GitHub erfolgte über ein Kanban Board in der Oberfläche "_Projects_" mit dem Titel "_IT2-Praxisprojekt_". Zunächst wurden die erforderlichen Aufgaben gemeinsam besprochen und geeignete Arbeitsschritte bzw. -pakete festgelegt. Anschließend wurden mithilfe des Boards Zuständigkeiten verteilt und sowohl Startpunkt, Fälligkeit und Abschlussdatum fixiert. Diese Festlegungen erfolgten zumeist während unregelmäßigen Zoom-Treffen, die außerdem dazu dienten, komplexe Probleme zu besprechen und neue Aufgaben zu verteilen.
Von der Vorgehensweise, die verschiedenen Elemente der Aufgabe auf mehrere Repositorien unserer beiden GitHub-Accounts zu verteilen, die dann später zu einem gemeinsamen Repositorium zusammengefügt werden sollten, wurde sehr schnell Abstand genommen, da sich dieses Vorgehen im weitern Verlauf als unpraktisch und sehr umständlich erwies.

Die Aufgabe IT2.1a hat uns geholfen, erste Erfahrungen mit der Plattform GitHub und ihren Grundfunktionen zu sammeln. Dennoch gestaltete sich die Bedienung und Orientierung auf der Plattform in diesem Projekt als Herausforderung, da vorher noch kein so umfassendes Projekt mithilfe eines Kanban Boards oder der Plattform GitHub umgesetzt wurde. Zudem bestanden Unklarheiten hinsichtlich möglicher Einstellungen, um ein Zusammenarbeit effektiver zu gestalten. Viele Komfort-Funktionen und Möglichkeiten wurden mutmaßlich aus diesem Grund nicht genutzt, da sie uns nicht bekannt waren. Auch die Abgrenzung geeigneter Arbeitspakete, die in sich geschlossen umsetzbar waren, konnten nicht immer eindeutig festgelegt werden. So stellte sich wiederholt heraus, dass mehrere Arbeitsschritte voneinander abhängig waren oder es ergaben sich in der Bearbeitung Lösungen, die das Festhalten an bestimmten Aufteilungen überflüssig machten. Das fehlende Vorwissen und die geringe Erfahrung zur Umsetzung einer solchen IT-Aufgabe trug hierzu nicht unwesentlich bei. Es gestaltete sich außerdem an einigen Punkten schwierig, jeden Schritt im Projekt gemeinsam zu gehen, da bestimmte Aufgaben nur durch eine Person sinnvoll umsetzbar waren. Trotz des regen Austauschs blieben die damit verbundenen Erfahrungen einer Person vorbehalten.

Für die Erstellung der Turtle-Datei haben wird den Systematik-Bereich 4.00 zunächst unter uns aufgeteilt, separat bearbeitet und anschließend beide Teile manuell zusammengefügt. Die Erstellung beider Teile erfolgte händisch. Eine automatisierte Transformation der Datengrundlage wurde nicht durchgeführt. Dadurch konnten umfassende Kenntisse der Datenstruktur gesammelt werden. 
Das manuelle Zusammeführen war den fehlenden Kenntnis über die Funktionen von GitHub geschuldet. Mittlerweile ist aber klar, dass die Weiterentwicklungen an einem Quellcode in der Regel in einem geforkten _Branch_ erfolgen. Sobald diese Weiterentwicklung abgeschlossen ist, kann die Änderung per _Pull-Request_ in den Quellcode übernommen werden. Anschließend findet ein _Merge_ zwischen Quellcode und _Branch_ statt. Nach der Zusammführung ergab sich für uns ein paar Probleme, wie z.B. dass die Hierarchie der einzelnen Systemstellen nichtkorrekt abgebildet wurden oder sich die Schreibweise ("_4.0_" statt "_4.00_" o.ä.) in beiden getrennt erstellten Teilen nicht übereinstimmte. Es war eine Herausforderung dies Abweichungen in der Datei zu erkennen und auszubessern. Ausgehend von einer bereinigten und funktionierenden Kernfassung wurden nach und nach die zusätzlichen Anforderungen aus der Aufgabenstellung in die Datei eingearbeit. Diese Änderungen wurden immer direkt über das Repositorium _committed_ und nicht in einem _Branch_ weiterentwickelt. Durch das Auftreten von Fehlern bei der Publikation des Vokabulars über ScoHub Vocabs konnten nach und nach die Bezüge zur Turtel-Datei erkannt und in den meisten Fällen durch die Trial-and-Error-Methode gelöst werden. 

<a name="3"></a>
## **3. Probleme beim Einrichten des Repositoriums**

Das Repositorium wurde von uns gemäß den bereitgestellten Orientierungshilfen insbesondere mit Hilfe der Workshop-Präsentationen eingerichtet. Besonders die dort beschriebene Konfiguration des Repositoriums war für uns gut nachvollziehbar. Ebenso hilfreich waren für uns die bereitgestellten Videos und das verlinkte Tutorial zur Einführung in SKOS. In manchen Fällen konnten den verlinkten Beispiel-Vokabularen Hinweise auf die richtige Syntax und die Funktion einzelner SKOS-Klassen entnommen werden.
  
Aus unserer Sicht wäre es zukünftig hilfreich die wichtigsten Informationen an einer Stelle zu bündeln, anstatt sehr viele verschiedene Orientierungshilfen und Quellen bereitzustellen. So kann Studierenden, die bisher wenig Erfahrung mit Repositorien in GitHub haben, ein besserer Zugang zur Aufgabe ermöglicht werden.

<a name="4"></a>
## **4. Verständnis von RDF und SKOS vor und nach Bearbeitung**

Vor der Arbeit am Projekt gab es für uns keine bzw. kaum Berührungspunkte mit SKOS oder RDF bzw. Turtle. Basisinformationen zu den verschiedenen Elementen, der Syntax und dem Grundaufbau von SKOS bzw. Turtle vermittelte – wie bereits erwähnt – das Tutorium.

Bei _RDF_ (Resource Description Framework) handelt es sich um ein Linked Open Data Datenmodel, in dem sich jede Informationseinheit aus drei Teilen nach dem Prinzip Subjekt, Prädikat, Objekt (Triple) zusammensetzt. RDF trifft also Aussagen über Ressourcen indem diese in Beziehung zu einem anderen Objekten oder einem Merkmal gesetzt werden.

Das Datenformat _Turtle_ (Terse RDF Triple Language) ist eine Serialiserung von RDF. Durch das eine gut lesbare, textbasierte Darstellung von RDF-Graphen möglich ist.

_SKOS_ (Simple Knowledge Organisation System) wiederum ist ein Datenstandard der einen Namensraum bereitstellt, um kontrollierte Vokabulare im Semantic Web veröffentlichen, nutzen und verknüpfen zu können.

<a name="5"></a>
## **5. Ausblick auf weitere Nutzungs- und Anwendungsfälle**

Ein wichtiger erster Schritt wäre zunächst die komplette Übertragung der Thesaurus-Systematik in SKOS, also die Einarbeitung aller 11 Hauptgruppen statt lediglich der Systemstelle 4.00. Anschließend können auch die Deskriptoren eingefügt und den Systemstellen zugeordnet werden (siehe Beispiel "Sicherheitsbehörden"). Auf diese Weise können Thesaurus-Systematik und Thesaurus miteinander verbunden werden.

In diesem Zusammenhang könnten dann auch weitere SKOS-Properties für die Deskriptoren eingesetzt werden wie z.B. altLabel und Mapping Properties zur Anbindung an andere kontrollierte Vokabulare wie z.B. Wikidata mit mappingRelation, closeMatch, exactMatch, broadMatch, narrowMatch, relatedMatch. Auf diese Weise kann der Thesaurus öffentlich zugänglich gemacht und von anderen Institutionen nachgenutzt werden. Die Inhalte können durch diese webkonforme Veröffentlichung des Vokabulars referenziert und in anderen Umgebungen im Sinne von Linked Open Data nachgenutzt werden. Allerdings widerspricht hier die Lizenz _CC BY-NC-SA_ zum Vokabular dem Grundgedanken von Linked Open Data und sorgt dafür, dass die Inhalte rechtlich nicht komplett offen nachgenutzt werden können. Die Lizenz schließt eine kommerzielle Nutzung der Inhalte durch den Zusatz „NC“ für „Non Commercial“ aus. Die Lizenzvergabe erfolgte in Rücksprache mit den Vorgesetzten und war eine Voraussetzung für die Umsetzung des Projekts. 

Bei der Erstellung der permanentens URIs wurde grundsätzlich eine potenzielle Erweiterung mitgedacht. So könnten sich an die URI "_purl.org/thesaurus_systematik/_" weitere Bundesbehörden und Informastionswissenschaftliche Einrichtungen anschließen, wenn sie Interesse daran haben ihre eigene Thesaurus-Systematik webkonform zu veröffentlichen.
