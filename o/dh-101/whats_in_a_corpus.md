# Projektskizze: What's in a corpus?

*Adrian Demleitner, University of Bern, FS 2023<br>**Einführung in die Digital Humanities***

## Abstrakt
Die vorliegende Projektskizze beschäftigt sich mit der Fragestellung, wie ein Korpus zur Erforschung der Visualität von alten digitalen Spielen aufgebaut werden kann. Im Rahmen eines praxisorientierten Teilprojekts der Dissertation werden die Schritte zur Erstellung und Strukturierung eines solchen Korpus untersucht.

## 1. Fragestellung und Problematik
Dieses Teilprojekt im angewandten Teil meiner Dissertation geht praxisorientiert der Fragestellung nach, wie ein Korpus zur Forschung an der Visualität von alten digitalen Spielen aufgebaut werden muss. Damit einhergehen Fragen danach, wie ein Korpus der zu erforschenden Spiele erstellt und strukturiert werden kann.

## 2. Datengrundlage und Korpora
Mein Dissertation ist Teil des Forschungsprojektes Confederatio Ludens, welches Schweizer Videospiele bis und mit dem Jahr 2000 untersuchen möchte. Die beiden Parameter *"Schweiz"* und *"bis und mit 2000"* bilden zusammen die Rahmung der zu untersuchenden Spiele. Der Parameter "Schweiz" ist dabei eher flexibel zu halten und wurde nicht im Detail definiert.

Die Liste der Spiele orientiert sich darum am Forschungsinteresse der Historizität der Spiele sowie der Akteure, welche an den Entwicklungen beteiligt waren. Ein anschauliches Beispiel ist das Spiel Necronom von 1991. Von den fünf Entwicklern war nur eine Person in der Schweiz wohnhaft und war auch nur aushelfend. Eine andere Person kam aus dem Vorarlberg, hatte aber zeitweise in der Schweiz gelebt. Die anderen drei Entwickler kamen aus England. Das Spiel wurde vom Schweizer Herausgeber Linel vertrieben und ist damit ein klares Beispiel einer frühen internationalen Kollaboration, welches im Osten der Schweiz seinen Ankerpunkt fand.

Eugen Pfister hatte 2022 eine erste Sammelaktion für digitale Spiele aus den deutschsprachigen Ländern ins Leben gerufen. Dabei ging es erst einmal um eine erste Übersicht und ein Herantasten. Eine ähnliche Liste hatte bis anhin noch nicht existiert. Dieses kollaborative Projekt hatte verschiedene Ansätze, vor allem jedoch die manuelle Durchsuchung nach Online-Datenbanken nach Ländern, Sprachen und Akteuren, aber auch die Durchforstung von alten Spielemagazinen nach Werbung und Listings. An der Erarbeitung und Kontrolle dieses Datenbestandes hatte ich mich aktiv beteiligt. Er bildet die Grundlage für mein eigenes Weiterarbeiten.

In meinem Teilprojekt konzentriere ich mich auf das visuelle dieser Spiele. Ein Korpus für dieses Material existiert noch nicht. Nebst der Schwierigkeit der zu erforschenden Spiele ergibt sich also auch die Frage, welches Material ich überhaupt untersuchen möchte. Derzeit konzentriere ich mich vor allem auf die qualitative Untersuchung, ein Close Reading der Visualität von Spielen, und komme mit dem eigenen Bildmaterial gut zurecht.

## 3. Methodisches Vorgehen
Um meinen Bildkorpus aufzubauen, verfolge ich das Prinzip des Spielens als Forschungsmethode sowie den "Assembling Auras" Ansatz von Guay Belanger. In vielen Fällen produziere ich dabei eigenes Bildmaterials, unter anderem Screenshots von ausgewählten Situationen im Spiel. Da Spiele ungleich einem Film eine gewisse Varianz in sich tragen, sowie die Schwierigkeit besteht, dass alte Spiele nur schwer akkurat wiedergegeben werden können, geht es in Belangers Ansatz darum, möglichst viel und diverses Bildmaterial zu einem Spiel zu sammeln. Dabei bin ich auf Online-Quellen wie spezialisierte Datenbanken oder Webseiten angewiesen.

Um diesen Quellen strukturiert nachzugehen, habe ich mich entschieden, den Schweiz-Anteil der DACH-Liste für Wikidata aufzubereiten. Wikidata ist laut Jean-Frederic Berthelot nicht eine Datenbank, um alle Datenbank zu ersetzen, sondern um diese untereinander zu verknüpfen. Dieser Ansatz kommt meinem Bedürfnis nach vielen verschiedenen Quellen nach.

Die FAIR und CARE Prinzipien waren ein weiterer Grund, warum ich mich für Wikidata entschieden hatte. Durch die Veröffentlichung der kollaborativen Arbeit an der Spiele-Datenbank kann ich sicherstellen, dass die Daten nachhaltig und frei verfügbar abgelegt sind. Wikidata ist nicht zwingend führend, wenn es um die Suche nach Datensätzen geht, jedoch kann dieses Problem mit vorbereiteten Suchanfragen relativ gut angegangen werden.

Ein wichtiges Werkzeug in der Arbeit mit Wikidata ist OpenRefine[^1]. OpenRefine ermöglicht Datenbereinigung und -umwandlung, oder was allgemein unter Data Wrangling verstanden wird. Die Grundlage der Arbeit in OpenRefine sind Daten in Tabellenform, also zum Beispiel Excel Dateien oder, wie in unserem Fall, die kollaborativ generierte Spiele-Liste in einem Google Sheets. Das Werkzeug ermöglicht sehr einfaches Abgleichen mit Wikidata, den Aufbau von Datenmodellen, und schlussendlich auch den Import der bereinigten Daten nach Wikidata.

## 4. Zwischenresultate und Diskussion
Ein erste Gesamtliste konnte relativ einfach kollaborativ und mit Fleissarbeit zusammen getragen werden. Probleme bereitet jedoch die Abstimmung der Metadaten auf der Detailebene.

### 4.1 Schwierigkeiten
Der Abgleich der eigenen Daten mit Wikidata durch OpenRefine ist ein einfacher Prozess. Die Reconcilation Funktion nimmt den Inhalt einer Spalte, welche Daten im gleichen Format und vom gleichen Typ enthalten, und lässt die Benutzer\*in Wikidata nach dem entsprechenden Attribut durchsuchen und abgleichen. Faktische Attribute wie zum Beispiel der Spiel-Titel sind einfach in ihrer Handhabe. Attribute, welche eine beschränkte Auswahl zulassen, welche jedoch nicht Forschungsfelder-übergreifend standardisiert ist, sind schwieriger. Zu nennen wären hier die Attribute country of origin, genre, aber auch die Zuschreibung von Tätigkeiten bei den Akteuren.

Das Attribut country of origin bezieht sich direkt auf unsere einfache Definition unseres Forschungskorpus. Was macht ein Schweizer Videospiel aus? Das digitale Spiel weist bezüglich seiner Verortung eine sehr hohe Unsicherheit auf. Diese Unsicherheit weist darauf hin, dass Videospiele in der Regel in Netzwerken aus geografisch verschiedenst lokalisierbaren Akteuren entstehen, was ein grundlegendes Merkmal digitaler Artefakte ist.

Schwierigkeiten bringt auch das Attribut genre. Je nach Perspektive muss dieses Attribut andere Informationen in sich tragen. Das Genre Breakout-Klone reiht ein Spiel in eine Historizität ein, während sidescrolling shooter auf den Spielmodus sowie die Visualität des Spieles eingeht. 

### 4.2 Zwischenresultate
Abgesehen davon, dass ich noch nicht am Bildkorpus arbeiten konnte, empfinde ich die Auseinandersetzung mit den Rohdaten des Korpus als extrem bereichernd. 

Das Akteur-Netzwerk legt derzeit die These nach, dass es wenig Austausch zwischen der deutsch- und der französischsprachigen Schweiz gab, jedoch zumindest in der Deutschschweiz auch internationale Kollaborationen stattfanden. Das schliesst Kollaborationen in der Romandie oder im Tessin nicht aus, jedoch fehlen mir für eine Aussage dazu noch die Befunde.

Um der Frage der Lokalisierung eines Spieles nachzugehen, empfinde ich es als wichtig, vor allem über die Akteure zu arbeiten. Das kann je nach Spiel sehr viel Aufwand mit sich bringen, da nicht nur die Attribute eines Artefaktes, sondern die Geschichte mehrerer Akteure aufgearbeitet werden muss.

Zum Thema des Genres wurde schon der eine oder andere Versuch einer Kanonisierung gestartet. Wikidata lässt mehrere Einträge pro Attribute zu, jedoch bedürfte es der genaueren Ausarbeitung, was ein Eintrag genau bezeichnet oder in welcher Disziplin dieser zu verankern wäre. Hierzu werde ich mich mit dem Video Game Project von Wikidata, der Arbeitsgruppe zu Videospielen, in Kontakt setzen.

## Bibliografie
Carroll, S. R., Garba, I., Figueroa-Rodríguez, O. L., Holbrook, J., Lovett, R., Materechera, S., Parsons, M., Raseroka, K., Rodriguez-Lonebear, D., Rowe, R., Sara, R., Walker, J. D., Anderson, J., & Hudson, M. (2020). The CARE Principles for Indigenous Data Governance. _Data Science Journal_, _19_(1), Article 1. [https://doi.org/10.5334/dsj-2020-043](https://doi.org/10.5334/dsj-2020-043)

Donaldson, S. (n.d.). _The Ephemeral Archive. Unstable Terrain in Times and Sites of Discord_. Debates in the Digital Humanities. Retrieved February 20, 2023, from [https://dhdebates.gc.cuny.edu/read/the-digital-black-atlantic/section/b5c2c6f7-c1a2-4645-8cf7-9d5cc70aa019#ch02](https://dhdebates.gc.cuny.edu/read/the-digital-black-atlantic/section/b5c2c6f7-c1a2-4645-8cf7-9d5cc70aa019#ch02)

Flanders, J., & Jannidis, F. (Eds.). (2019). _The shape of data in the digital humanities_. Routledge, Taylor & Francis Group.

Guay-Bélanger, D. (2022). Assembling Auras: Towards a Methodology for the Preservation and Study of Video Games as Cultural Heritage Artefacts. _Games and Culture_, _17_(5), 659–678. [https://doi.org/10.1177/15554120211020381](https://doi.org/10.1177/15554120211020381)

Pfister, E., & Görgen, A. (2022, March 8). How to analyse a Video game from a historical, source-critical perspective: The HGP-Method [Billet]. _Horror - Game - Politics_. [https://hgp.hypotheses.org/1754](https://hgp.hypotheses.org/1754)

Pfister, E., & Winnerling, T. (2020). _Digitale Spiele und Geschichte: Ein kurzer Leitfaden für Student*innen, Forscher*innen und Geschichtsinteressierte_. vwh Verlag Werner Hülsbusch, Fachverlag für Medientechnik und -wirtschaft.

Pomerantz, J. (2015). _Metadata_. The MIT Press.

Rehbein, M. (2017). Ontologien. In F. Jannidis, H. Kohle, & M. Rehbein (Eds.), _Digital Humanities: Eine Einführung_ (pp. 162–176). J.B. Metzler. [https://doi.org/10.1007/978-3-476-05446-3_11](https://doi.org/10.1007/978-3-476-05446-3_11)

Rheinberger, H.-J. (n.d.). _Wie werden aus Spuren Daten, und wie verhalten sich Daten zu Fakten?_

Stoler, A. L. (2007). The Pulse of the Archive. _Ab Imperio_, _2007_(3), 225–264. [https://doi.org/10.1353/imp.2007.0050](https://doi.org/10.1353/imp.2007.0050)

_View of Zooming into an Instagram City: Reading the local through social media | First Monday_. (n.d.). Retrieved April 24, 2023, from [https://firstmonday.org/ojs/index.php/fm/article/view/4711/3698](https://firstmonday.org/ojs/index.php/fm/article/view/4711/3698)

Wilkinson, M. D., Dumontier, M., Aalbersberg, Ij. J., Appleton, G., Axton, M., Baak, A., Blomberg, N., Boiten, J.-W., da Silva Santos, L. B., Bourne, P. E., Bouwman, J., Brookes, A. J., Clark, T., Crosas, M., Dillo, I., Dumon, O., Edmunds, S., Evelo, C. T., Finkers, R., … Mons, B. (2016). The FAIR Guiding Principles for scientific data management and stewardship. _Scientific Data_, _3_(1), Article 1. [https://doi.org/10.1038/sdata.2016.18](https://doi.org/10.1038/sdata.2016.18)

[^1]: https://openrefine.org