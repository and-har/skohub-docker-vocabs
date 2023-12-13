# **Publikation eines kontrollierten Vokabulars mit SkoHub Vocabs**
## **Projektbericht im Modul MALIS 23.2 IT 2 - Dozent: Adrian Pohl** 
### **Aufgabe: Kleines Projekt IT 2**

**vorgelegt von:**


**Andreas Hartmann**

XX

Matrikelnummer: 

und 


**Benjamin Helmut Heu**

benjamin_helmut.heu@smail.th-koeln.de

Matrikelnummer: 11188281


## **1. Beschreibung des gewählte Vokabulars**

Es wurde sich für ein Vokabular entschieden, das im _Bundesamt für Migration und Flüchtlinge_ in der Literaturdokumentation zur Klassifikation von Deskriptoren verwendet wird. Dabei werden die Deskriptoren den Systemstellen der Systematik zugewiesen. Auf diese Weise kann unter anderem die Sy­n­o­ny­mie von Begriffen abgebildet werden, die je nach Systemstelle einen anderen Bedeutungskontext haben können. So ist etwa der Deskriptor "_Sicherheitsbehörde_" sowohl der Systemstelle 4.35 für "_Öffentliche Verwaltung, staatliche Gliederung_" als auch 4.51 für "_Polizei und nichtmilitärische Sicherheitsorgane_" zugeordnet. Die Systematik dient somit der klassifikatorischen Erschließung von Sachbegriffen.

Inhaltlich basiert die Systematik teilweise auf der _EMN Glossary on Asylum and Migration Classification_, wurde für die Literaturdokumentation des Bundesamtes jedoch ergänzt. Zum jetzigen Stand besteht sie insgesamt aus elf Hauptgruppen und 205 Systemstellen, von denen im Rahmen des Projektes die Hauptgruppe 4.00 mit ihren Untergruppen ausgewählt und ins Englische übersetzt wurde. Die Hauptgruppe 4.00 umfasst insgesamt acht Teilgruppen (4.10 bis 4.80), von denen die Gruppen 4.30 bis 4.60 wiederum weitere Untergruppen enthalten. Daraus ergeben sich insgesamt 27 Systemstellen, die im Rahmen des Projektes bearbeitet wurden.

Bisher existiert keine geeignete Software zur Verwaltung und Pflege der Thesaurus-Systematik. Außerdem ist der Export in ein anderes System aktuell mit einem großen Aufwand verbunden, da die Systematik in keinem Austauschformat vorliegt. Die Übertragung der Thesaurus-Systematik in das SKOS-Format ist daher ein erster wichtiger Schritt für den Datenaustausch und -export sowie das Anlegen von Crosskonkordanzen zu anderen Systematiken.



   
(**Aufgabe:** *"Beschreibung des gewählten Vokabulars (Anzahl der Deskriptoren, benutzten Sprachen etc.) seines Anwendungsbereichs und Begründung der Auswahl gerade dieses Vokabulars"*)

- Verwendung im Bundesamt für Migration und Flüchtlinge in der Literaturdokumentation zur Klassifikation von Deskriptoren
- die Deskriptoren werden den Systemstellen in der Systematik zugewiesen, auf diese Weise kann z.B. die Sy­n­o­ny­mie von Begriffen abgebildet werden, da diese je nach Systemstelle einen anderen Bedeutungskontext haben können z.B. der Deskriptor "Sicherheitsbehörde" ist sowohl der Systemstelle 4.35 für "Öffentliche Verwaltung, staatliche Gliederung" und 4.51 für "Polizei und nichtmilitärische Sicherheitsorgane" zugeordnet
- die Systematik dient damit der klassifikatorischen Erschließung von Sachbegriffen
- die Systematik basiert teilweise auf dem EMN Glossary on Asylum and Migration Classification und wurde für die Literaturdokumentation im Bundesamt aber um weitere Hauptgruppen erweitert
- die Systeamtik besteht insgesamt auf elf Hauptgruppen und aus insgesamt 205 Systemstellen
- im Rahmen des IT-Projekt wurde die Hauptgruppe 4.00 mit ihren Untergruppen umgesetzt
- das Vokabular lag bisher nur in deutscher Sprache vor
- für das Projekt wurden die Systemstellen der Gruppe 4.00 ins englische übersetzt
- die Hauptgruppe 4.00 enhält insgesamt 8 Gruppen (4.10-4.80), dabei haben die Gruppen 4.30-4.60 weitere Untergruppen
- insgesamt enthält die Hauptgruppe 4.00 insgesamt 27 Systemstellen
- bisher exisitert keine geeignete Software zur Verwaltung und Pflege der Thesaurus-Systematik, ebenso ist der Export in ein anderes System aktuelle mit großem Aufwand verbunden, da die Systematik in keinem Austauschformat vorliegt
- die Übersetzung der Thesaurus-Systematik in das SKOS-Format wäre daher ein erster wichtiger Schritt für den Datenaustausch und -export sowie das Anlegen von Crosskonkordanzen zu anderen Systematiken

## **2. Zusammenarbeit mit GitHub**

Grundsätzlich war das Vorgehen vor allem in der Anfangsphase durch _agile Elemente_ geprägt: Es wurde zunächst eine funktionierende Kernfassung unserer Turtle-Datei erstellt, in die dann nach und nach die zusätzlichen Anforderungen eingearbeitet wurden.

Von der ursprünglichen Vorgehensweise, die verschiedenen Elemente der Aufgabe auf mehrere Repositorien unserer beiden Accounts zu verteilen, die dann später zu einem gemeinsamen Repositorium zusammengefügt werden sollten, wurde sehr schnell Abstand genommen, da sich dieses Vorgehen als unpraktisch und sehr umständlich erwiesen hatte.

Die Zusammenarbeit erfolgte stattdessen über ein _Kanban Board in GitHub_. Dazu wurden zunächst Aufgaben gemeinsam besprochen und geeignete Arbeitsschritte bzw. -pakete festgelegt. Anschließend wurden mithilfe des Boards Zuständigkeiten verteilt und sowohl Startpunkt, Fälligkeit und Abschlussdatum fixiert. Diese Festlegungen erfolgten zumeist während unregelmäßiger Zoom-Treffen, die außerdem dazu dienten, komplexe Probleme zu besprechen und die zuvor genannten Aufgaben zu verteilen.

Die konkrete Arbeit an der Turtle-Datei gestaltete sich so, dass Änderungen immer direkt über das Repositorium committed und nicht in einer Verzweigung weiterentwickelt und später zusammengeführt wurden.

Die Aufgabe T2.1a hat uns zwar geholfen, die Plattform GitHub und ihre Funktionen kennenzulernen, dennoch hielt die Bearbeitung des Projekts einige _Schwierigkeiten_ bereit. Drei Punkte sollen besonders genannt werden:

- Da vorher noch kein Projekt mit einem Kanban Board oder der Plattform GitHub umgesetzt wurde, war die _Bedienung und Orientierung auf der Plattform_ zunächst eine Herausforderung. Viele Komfort-Funktionen und Möglichkeiten wurden mutmaßlich aus diesem Grund nicht genutzt, da sie uns nicht bekannt waren.

- Als besondere Herausforderung stellte sich die _Abgrenzung geeigneter Arbeitspakte_ dar, die in sich geschlossen umsetzbar waren. So stellte sich wiederholt heraus, dass mehrere Arbeitsschritte voneinander abhängig waren oder es ergaben sich in der Bearbeitung Lösungen, die das Festhalten an bestimmten Aufteilungen überflüssig machten. Die fehlende Expertise in der Umsetzung von IT-Projekten trug hierzu nicht unwesentlich bei.

- Es gestaltete sich außerdem an einigen Punkten schwierig, _jeden Schritt im Projekt gemeinsam_ zu gehen, da bestimmte Aufgaben nur durch eine Person sinnvoll umsetzbar waren. Trotz des regen Austauschs blieb die damit verbundene Erfahrung einer Person vorbehalten.


(**Aufgabe:** *"Zusammenarbeit mit git und auf GitHub und – falls Sie das nutzen – unter Pflege eines gemeinsamen Kanban Boards. Wie hat es funktioniert? Was wurde gelernt? Wo sind noch Probleme?"*)

- die Zusammenarbeit erfolgte über ein Kanban Board in GitHub
- Aufgaben wurde gemeinsam besprochen und dafür geeignete Arbeitsschritte definiert
- mithilfe des Boards wurde die Zuständigkeiten verteilt, Startpunkt, Fälligkeit und Abschlussdatum definiert
- da vorher noch kein Projekt mit einem Kanban Board oder der Plattform GitHub umgesetzt wurde, war die Bedienung und Orientierung auf der Plattform zunächst eine Herausforderung
- viele Komfort-Funktionen und Möglichkeiten wurde sicherlich auch aus diesem Grund nicht genutzt, da schlichtweg nicht bekannt
- es war nicht immer einfach, vorab geeignete Arbeitsschritte (Arbeitspakete) festzulegen die in sich geschlossen umsetzbar waren
- häufig waren mehrere Arbeitspaket voneinander abhängig oder in der Umsetzung ergaben sich Lösungen, die das Aufteilen von Arbeitspaketen überflüssig machten
- diese Problematik ergibt sich sicherlich auch aus der fehlende Expertise bei der Umsetzung von IT-Projekten
- es gestaltet sich auch als ziemlich schwierig jeden Schritt im Projekt gemeinsam zu gehen, da bestimmte Aufgaben sinnvoll nur durch eine Person umsetzbar waren, somit blieb die Erfahrung einer Person vorbehalten
- Wie kann man eine solchen Prozess sinnvoll in Arbeitspakete zerlegen?
- Neben der Organisation über GitHub waren auch unregelmäßige Treffen Teil der Umsetzung, um Probleme zu schildern und neue Aufgaben zu definieren und zu verteilen
- die Aufgabe T2.1a hat geholfen die Plattform GitHub und ihre Funktionen besser kennenzulernen
- Änderungen am der Turtle-Datei wurden immer über direkt über das Repository committed und nicht in einer Verzweigung weiterentwickelt und später zusammengeführt
- Grundsätzlich war das Vorgehen vor allem in der Anfangsphase durch agile Elemente geprägt: Es wurde zunächst eine funktionierende Rumpffassung erstellt in die dann nach und nach die zusätzlichen Anforderungen eingearbeitet wurden
- Von der ursprünglichen Vorgehensweise, die verschiedenen Elemente der Aufgabe auf mehrere Repositorien der beiden Accounts zu verteilen, die dann später zu einem gemeinsamen Repositorium zusammengefügt werden sollten, wurde sehr schnell Abstand genommen, da sich dieses Vorgehen als unpraktisch und umständlich erwiesen hatte. 

## **3. Probleme beim Einrichten des Repos**
(**Aufgabe:** *"Probleme beim Einrichten des Repos (Wie kann die Dokumentation verbessert werden?)"*)

- das Repo wurde gemäß den bereitgestellten Orientierunghilfen (Workshop-Präsentationen) eingerichtet
- die Konfiguration für das Repo war gut nachvollziehbar
- das korrekte Erstellen der der Turtle-Datei war eine größere Herausfoderung
- es war nicht klar welche "@base"-URL anzugeben ist und das hier eine Verknüpfung zu den Perma-URIs besteht
- die Zusammenhänge zwischen Turtel-Datei und publiziertem Vokabular konnten in den meisten Fällen durch die Trial-and-Error-Methode gelöst werden
- In manchen Fällen konnten die verlinkten Beispiel-Vokabulare auch Hinweise zur Syntax und dem grundsätzlichen Aufgabe von SKOS-Konzepten geben
- es ist nicht klar welche Einstellungen für eine effektive Zusammenarbeit am Repo gemacht werden müssen
- Das verlinkte Tutorial war sehr hilfreich
- -Ebenso hilfreich waren die bereitgestellten Videos. 
- hilfreich wäre es zukünftig die wichtigsten Informationen an einer Stelle zusammenzufassen, anstatt sehr viele verschiedene Orientierungshilfen bereitzustellen
- Mithilfe der Einführung in SKOS konnte die .ttl-Datei in seinen Grundzügen angelegt werden
- bei der Umsetzung der .ttl-Datei haben wird die Systematikstelle 4.00 zuerst in zwei Teile geteilt und später miteinander verbunden
- eine Herausfoderung war es in diesem Fall die unterschiedlichen Schreibweisen zu vereinheitlichen und diese auch im Code zu erkennen z.B. 4.0 statt 4.00
- die Hierarchie der einzelnen Systemstellen nach dem Verbinden korrekt abzubilden war ebenfalls eine Herausforderung
- das Verbinden wurde händisch einfügen und nicht über eine Pull-Request umgesetzt, was mit der fehlende Kenntnis über den Arbeitsablauf in zusammenhängt GitHub
- mittlerweile ist aber klar, dass Entwicklungen an einem Quellcode in GitHub zur Versionsverwaltung in der Regel in einem geforkten Branch erfolgen, sobald diese Weiterentwicklung abgeschlossen ist, kann die Änderung per Pull Request in den Quellcode übernommen werden sofern diese vorab akzeptiert wurde
- anschließend findet ein Merge zwischen Quellcode und Anpassung/Änderung statt

## **4. Verständnis vor und nach Bearbeitung RDF/SKOS**
(**Aufgabe:** *"Verständnis von RDF und SKOS vor und nach Bearbeitung der Aufgabe."*)

- Vor der Arbeit am Projekt gab es keine bzw. kaum Berührungspunkte mit SKOS oder RDF bzw. turtle
- Basisinformationen zu den verschiedenen Elementen, der Syntax und dem Grundaufbau von SKOS bzw. turtle vermittelte wiederum das Tutorium.
- RDF (Ressource Description Framwork) ist ein Datenmodel für Liked Open Data, dabei setzt sich jede Informartionseinheit aus drei Teilen nach dem Prinzip Subjekt, Prädikat, Objekt (Triple) zusammen (Entity-Relationship-Model)
- RDF trifft Aussagen über Ressourcen
- eine Serialiserung von RDF ist Turtle (Terse RDF Triple Language) und ermöglich ein gut lesbare textbasierte Darstellung von RDF-Graphen 
- SKOS (Simple Knowledge Organisation System) wiederrum ist ein Datenstandard der einen Namensraum bereitstellt, um kontrollierte Vokabulare im Semantic Web veröffentlichen, nutzen und verknüpfen zu können
- 

## **5. Ausblick und Nutzen/Anwendungsfälle**
(**Aufgabe:** *"Ausblick: Was ist durch die SKOS-Repräsentation des Vokabulars und seiner Publikation im Web gewonnen? Welche Anwendungsfälle werden nun ermöglicht?"*)

- zunächst sollte die Thesaurus-Systematik komplett in SKOS übertragen werden, alle 11 Hauptgruppen
- anschließend können auch die Dekriptoren eingefügt (allerdings ohne Begriffnotationen) und den Systemstellen zugeordnet werden (siehe Beispiel "Sicherheitsbehörden")
- somit lässt sich Thesaurus-Systematik und Thesaurus miteinander verbinden
- in diesem Zusammenhang können dann auch weitere SKOS-Proporties für die Deskriptoren eingesetzt werden wie z.B. altLabel und Mapping Properties zur Anbindung an andere kontrollierte Vokabulare wie z.B. Wikidata mit mappingRelation, closeMatch, exactMatch, broadMatch, narrowMatch, relatedMatch u.ä.
- der Thesaurus wird auf diese Weise öffentlich zugänglich und kann von anderen Institutionen nachgenutzt werden
- so könnten z.B. alle Behördenbibliotheken ihre eigene Thesaurus-Systmatiken mit der des Bundesamtes verknüpfen
