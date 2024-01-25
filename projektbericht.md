# **Publikation eines kontrollierten Vokabulars mit SkoHub Vocabs**
## **Projektbericht im Modul MALIS 23.2 IT 2 - Dozent: Adrian Pohl** 
### **Aufgabe: Kleines Projekt IT 2**

**vorgelegt von:**


**Andreas Hartmann**

und 

**Benjamin Heu**


## Inhaltsübersicht

- [1. Beschreibung des gewählten Vokabulars] (#1)
- [2. Zusammenarbeit auf Github] (#2. Zusammenarbeit mit Github)
- [3. Probleme beim Einrichten des Repositoriums] (#3. Probleme beim Einrichten des Repos)
- [4. Verständnis von RDF/SKOS vor und nach Bearbeitung] (#4)
- [5. Ausblick und Nutzen/Anwendungsfälle] (#5. Ausblick und Nutzen/Anwendungsfälle)

<a name="1"></a>
## **1. Beschreibung des gewählten Vokabulars**

Das gewählte Vokabular wird im _Bundesamt für Migration und Flüchtlinge_ in der Literaturdokumentation zur Klassifikation von Deskriptoren verwendet. Die einzelnen Deskriptoren werden je nach inhaltlicher Entsprechung einer oder mehreren Systemstellen der Systematik zugeordnet. Auf diese Weise kann eine bestehende Sinnverwandtschaft von Deskriptoren abgebildet werden, die je nach Zuordnung zu einer Systemstelle inhaltlich einen anderen Bedeutungskontext haben können. So ist etwa der Deskriptor "_Sicherheitsbehörde_" sowohl der Systemstelle 4.35 für "_Öffentliche Verwaltung, staatliche Gliederung_" als auch 4.51 für "_Polizei und nichtmilitärische Sicherheitsorgane_" zugeordnet. Die Systematik dient in erster Linie somit der klassifikatorischen Erschließung von Deskriptoren.

Inhaltlich basiert die Systematik teilweise auf der _EMN Glossary on Asylum and Migration Classification_, wurde für die Literaturdokumentation des Bundesamtes jedoch erweitert. Aktuell besteht sie aus insgesamt elf Hauptgruppen und 205 Systemstellen, von denen im Rahmen dieses Projektes die Hauptgruppe 4.00 „Politik und Sicherheitsfragen“ mit ihren Untergruppen ausgewählt und ins Englische übersetzt wurde. Die Hauptgruppe 4.00 umfasst insgesamt acht Teilgruppen (4.10 bis 4.80), von denen die Gruppen 4.30 bis 4.60 wiederum weitere Untergruppen enthalten. Daraus ergeben sich insgesamt 27 Systemstellen, die im Rahmen des Projektes bearbeitet und in SKOS-Konzepte übersetzt wurden.

Bisher existiert keine geeignete Software zur Verwaltung und Pflege der Thesaurus-Systematik. Außerdem ist ein Export der Systematik in ein anderes System bisher nicht möglich, da Sie in keinem entsprechenden Austauschformat vorliegt. Die Datengrundlage ist lediglich ein PDF-Dokument.Die Übertragung der Thesaurus-Systematik in das SKOS-Format ist daher ein erster wichtiger Schritt für den Datenaustausch und -export sowie das Anlegen von Crosskonkordanzen zu anderen Systematiken.

![eb90707a-e174-44ad-a19c-9254c062e5ec](https://github.com/and-har/thesaurus_systematik/assets/148260522/9b1c419d-9c3c-47bd-9c9d-59419eb346d9)

## **2. Zusammenarbeit auf GitHub**

Grundsätzlich war das Vorgehen vor allem in der Anfangsphase durch agile Elemente geprägt: Es wurde zunächst eine funktionierende Kernfassung unserer Turtle-Datei erstellt, in die dann nach und nach die zusätzlichen Anforderungen eingearbeitet wurden. Die Erstellung der Turtel-Datei an sich erfolgte händisch ohne eine automatisierte Transformation.

Von der ursprünglichen Vorgehensweise, die verschiedenen Elemente der Aufgabe auf mehrere Repositorien unserer beiden Accounts zu verteilen, die dann später zu einem gemeinsamen Repositorium zusammengefügt werden sollten, wurde sehr schnell Abstand genommen, da sich dieses Vorgehen als unpraktisch und sehr umständlich erwiesen hatte.

Die Zusammenarbeit erfolgte stattdessen über ein Kanban Board in GitHub. Dazu wurden zunächst Aufgaben gemeinsam besprochen und geeignete Arbeitsschritte bzw. -pakete festgelegt. Anschließend wurden mithilfe des Boards Zuständigkeiten verteilt und sowohl Startpunkt, Fälligkeit und Abschlussdatum fixiert. Diese Festlegungen erfolgten zumeist während unregelmäßigen Zoom-Treffen, die außerdem dazu dienten, komplexe Probleme zu besprechen und die zuvor genannten Aufgaben zu verteilen.

Die konkrete Arbeit an der Turtle-Datei gestaltete sich so, dass Änderungen immer direkt über das Repositorium _committed_ und nicht in einer Verzweigung weiterentwickelt und später zusammengeführt wurden.

Die Aufgabe IT2.1a hat uns zwar geholfen, die Plattform GitHub und ihre Funktionen kennenzulernen, dennoch hielt die Bearbeitung des Projekts einige Schwierigkeiten bereit. Da vorher noch kein vollständiges Projekt mithilfe eines Kanban Boards oder der Plattform GitHub umgesetzt wurde, war die Bedienung und Orientierung auf der Plattform zunächst eine Herausforderung. Viele Komfort-Funktionen und Möglichkeiten wurden mutmaßlich aus diesem Grund nicht genutzt, da sie uns nicht bekannt waren.
Als besondere Herausforderung stellte sich die Abgrenzung geeigneter Arbeitspakete dar, die in sich geschlossen umsetzbar waren. So stellte sich wiederholt heraus, dass mehrere Arbeitsschritte voneinander abhängig waren oder es ergaben sich in der Bearbeitung Lösungen, die das Festhalten an bestimmten Aufteilungen überflüssig machten. Die fehlende Expertise in der Umsetzung von IT-Projekten trug hierzu nicht unwesentlich bei.
Es gestaltete sich außerdem an einigen Punkten schwierig, jeden Schritt im Projekt gemeinsam zu gehen, da bestimmte Aufgaben nur durch eine Person sinnvoll umsetzbar waren. Trotz des regen Austauschs blieb die damit verbundenen Erfahrungen einer Person vorbehalten.

## **3. Probleme beim Einrichten des Repositoriums**

Das Repositorium wurde von uns gemäß den bereitgestellten Orientierungshilfen (vor allem der Workshop-Präsentationen) eingerichtet. Besonders die dort beschriebene Konfiguration des Repositoriums war für uns gut nachvollziehbar. Ebenso hilfreich waren für uns die bereitgestellten Videos und das verlinkte Tutorial zur Einführung in SKOS. In manchen Fällen konnten den verlinkten Beispiel-Vokabularen Hinweise zu einer sinnvollen Syntax und der Funktion einzelner SKOS-Konzepte entnommen werden.

Für die Erstellung der Turtle-Datei haben wird den Systematik-Bereich 4.00 zunächst unter uns aufgeteilt und separat bearbeitet. Anschließend haben wir beide Teile zusammengefügt. . Die Herausforderung, die sich daraus ergab, war, dass die Hierarchie der einzelnen Systemstellen nach der Verbindung korrekt abgebildet werden musste. Das Verbinden selbst wurde manuell und nicht über eine Pull-Request umgesetzt, was unserer fehlenden Kenntnis der maschinellen Arbeitsabläufe in GitHub geschuldet war. Mittlerweile ist aber klar, dass Entwicklungen an einem Quellcode in GitHub zur Versionsverwaltung in der Regel in einem geforkten Branch erfolgen. Sobald diese Weiterentwicklung abgeschlossen ist, kann die Änderung per Pull Request in den Quellcode übernommen werden sofern diese vorab akzeptiert wurde. Anschließend findet ein Merge zwischen Quellcode und Anpassung bzw. Änderung statt. Eine weitere Herausforderung war, die unterschiedlichen Schreibweisen zu vereinheitlichen und diese auch in der Datei zu erkennen (z.B. 4.0 statt 4.00) und abzuändern.

Zudem bestanden Unklarheiten hinsichtlich möglicher Einstellungen für eine effektive Zusammenarbeit am Repositorium, was den fehlenden Kenntnissen der Arbeitsumgebung geschuldet war.
  
Im weiteren Verlauf konnten Zusammenhänge zwischen Turtel-Datei und publiziertem Vokabular in den meisten Fällen durch die Trial-and-Error-Methode gelöst werden.
  
Aus unserer Sicht wäre es zukünftig hilfreich die wichtigsten Informationen an einer Stelle zu bündeln, anstatt sehr viele verschiedene Orientierungshilfen und Quellen bereitzustellen. So kann für Studierende, die bisher wenig Erfahrung im Umgang mit GitHub und der Arbeit mit Repositorien haben, ein besserer Zugang zur Aufgabe ermöglicht werden.

## **4. Verständnis vor und nach Bearbeitung RDF/SKOS**

Vor der Arbeit am Projekt gab es für uns keine bzw. kaum Berührungspunkte mit SKOS oder RDF bzw. Turtle. Basisinformationen zu den verschiedenen Elementen, der Syntax und dem Grundaufbau von SKOS bzw. Turtle vermittelte – wie bereits erwähnt – das Tutorium.
Bei _RDF_ (Resource Description Framework) handelt es sich um ein Linked Open Data Datenmodel , in dem sich jede Informationseinheit aus drei Teilen nach dem Prinzip Subjekt, Prädikat, Objekt (Triple) zusammensetzt (Entity-Relationship-Model). RDF trifft also Aussagen über Ressourcen indem diese in Beziehung zu einem anderen Objekten oder einem Merkmal gesetzt werden.
Das Datenformat _Turtle_ (Terse RDF Triple Language) ist eine Serialiserung von RDF. Durch das eine gut lesbare, textbasierte Darstellung von RDF-Graphen möglich ist.
_SKOS_ (Simple Knowledge Organisation System) wiederum ist ein Datenstandard der einen Namensraum bereitstellt, um kontrollierte Vokabulare im Semantic Web veröffentlichen, nutzen und verknüpfen zu können.

## **5. Ausblick und Nutzen/Anwendungsfälle**

Ein wichtiger erster Schritt wäre zunächst die komplette Übertragung der Thesaurus-Systematik in SKOS, also die Einarbeitung aller 11 Hauptgruppen statt lediglich der Systemstelle 4.00. Anschließend können auch die Deskriptoren eingefügt und den Systemstellen zugeordnet werden (siehe Beispiel "Sicherheitsbehörden"). Auf diese Weise können Thesaurus-Systematik und Thesaurus miteinander verbunden werden.

In diesem Zusammenhang könnten dann auch weitere SKOS-Properties für die Deskriptoren eingesetzt werden wie z.B. altLabel und Mapping Properties zur Anbindung an andere kontrollierte Vokabulare wie z.B. Wikidata mit mappingRelation, closeMatch, exactMatch, broadMatch, narrowMatch, relatedMatch. Auf diese Weise kann der Thesaurus öffentlich zugänglich gemacht und von anderen Institutionen nachgenutzt werden. Die Inhalte können durch diese webkonforme Veröffentlichung des Vokabulars referenziert und in anderen Umgebungen im Sinne von Linked Open Data nachgenutzt werden. Allerdings widerspricht hier die Lizenz CC BY-NC-SA zum Vokabular dem Grundgedanken von Linked Open Data und sorgt dafür, dass die Inhalte rechtlich nicht komplett offen nachgenutzt werden können. Die Lizenz schließt eine kommerzielle Nutzung der Inhalte durch den Zusatz „NC“ für „Non Commercial“ aus. Die Lizenzvergabe erfolgte in Rücksprache mit den Vorgesetzten und war eine Voraussetzung für die Umsetzung des Projekts.
