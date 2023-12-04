### MALIS 2023 Kleines IT2-Praxisprojekt in Zweier- oder Dreiergruppen
# Publikation eines kontrollierten Vokabulars mit SkoHub Vocabs

**Abgabefrist:** 27.01.2024<br>**Benotung:** Das Projekt zählt mit 50%iger Gewichtung zur Gesamtnote für das Modul
IT2.<br>**Workload:** Maximal 50 Stunden pro Person

## Aufgabenstellung
- Identifikation eines an der eigenen Einrichtung genutzten kontrollierten
Vokabulars (Werteliste, Klassifikation, Thesaurus), das noch nicht in SKOS
kodiert vorliegt.
- Überführung des Vokabulars in eine SKOS-kodierte Repräsentation.
- Publizieren des Vokabulars mit SkoHub Vocabs (Docker-Version, verfügbar
über https://github.com/skohub-io/skohub-docker-vocabs).

## Ergebnisse:
- git-Repositorium
  - Projekt-Kanban-Board (optional)
- Mit SkoHub Vocabs publiziertes SKOS-Vokabular
- Projektbericht

## Bewertungskriterien
- Methodik
  - Auswahl des Vokabulars und kontextuelle Einordnung
  - Organisation der Zusammenarbeit in einem GitHub-/GitLab-Repo, ggf. mit Kanban Board
  - Wenn möglich, sinnvoll und umsetzbar semi-automatisierte Transformation nach SKOS
- Der Bericht sollte idealerweise als Markdown-Datei im Projekt-Repo liegen, eine angemessene sprachliche Qualität haben und sinnvoll strukturiert sein.
- Das Vokabular sollte
  - entweder mindestens zwanzig SKOS-Konzepte umfassen, wobei die
Textstrings (skos:prefLabel, dct:title, dct:description sowie ggf.
skos:altLabel, skos:definition. skos:scopeNote) neben Deutsch in
mindestens einer weiteren Sprache vorliegen
  - oder mindestens 50 SKOS-Konzepte umfassen, die nur ein einer Sprache
vorliegen müssen
  - Das Gesamtvokabular soll neben dct:title und dct:description mindestens
zwei weitere informative Aussagen enthalten.
  - Neben den grundlegenden SKOS-Properties (hasTopConcept,
topConceptOf, inScheme, prefLabel), sollten mindestens drei zusätzliche
Properties sinnvoll genutzt werden.
  - Alternativ zur Publikation eines größeren Vokabulars können auch mehrere
kleine veröffentlicht werden.
  - Idealerweise sollten langfristig verfügbare URIs verwendet werden, z.B.
durch Nutzung von w3id.org oder purl.org.

## Lernziele
Die Teilnehmer:innen können nach der Bearbeitung der Aufgabe:
- ein git-Repositorium auf GitHub forken und einrichten,
- ein kontrolliertes Vokabular in strukturierter, maschinenlesbarer Form mit
SKOS abbilden,
- eine menschenlesbare Sicht des Vokabulars mit SkoHub Vocabs publizieren,
- die Umsetzung reflektieren etwa anhand folgender Leitgedanken:
  - Beschreibung des gewählten Vokabulars (Anzahl der Deskriptoren,
benutzten Sprachen etc.) seines Anwendungsbereichs und Begründung
der Auswahl gerade dieses Vokabulars
  - Zusammenarbeit mit git und auf GitHub und – falls Sie das nutzen – unter
Pflege eines gemeinsamen Kanban Boards. Wie hat es funktioniert? Was
wurde gelernt? Wo sind noch Probleme?
  - Probleme beim Einrichten des Repos (Wie kann die Dokumentation
verbessert werden?)
  - Verständnis von RDF und SKOS vor und nach Bearbeitung der Aufgabe.
  - Ausblick: Was ist durch die SKOS-Repräsentation des Vokabulars und
seiner Publikation im Web gewonnen? Welche Anwendungsfälle werden
nun ermöglicht?

## Orientierungshilfen
- Einführung in SKOS am Beispiel von Open Educational Resources (OER):
https://dini-ag-kim.github.io/skos-einfuehrung/
- SkoHub-Slides eines SKOS-Workshops von 30. November 2022:
https://pad.gwdg.de/p/2022-11-30-swib22-skos-workshop-slides
  - Fork und Setup des SkoHub-Docker-Vocabs-Repositories wird Schritt für
Schritt ab Folie 51 erläutert: https://pad.gwdg.de/p/2022-11-30-swib22-skos-workshop-slides#/51
- Anleitung zur Konfiguration von Perma-URIs mit W3ID oder purl.org:
https://git.io/JPWsI
- Beispielvokabulare:
  - Hochschulfächersystematik nach Destatis ([Vokabular](https://w3id.org/kim/hochschulfaechersystematik/scheme), [Repo](https://github.com/dini-ag-kim/hochschulfaechersystematik))
  - Interdisziplinäre Forschungsfeldklassifikation ([Vokabular](https://w3id.org/kdsf-ffk/), [Repo](https://github.com/KDSF-FFK/kdsf-ffk))
- Aufsetzen eines Kanban Boards mit GitHub Projects:
https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/quickstart-for-projects
