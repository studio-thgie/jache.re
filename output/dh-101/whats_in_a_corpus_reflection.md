---
created: 2023-11-09T19:30
updated: 2023-11-09T19:30
---
# Reflexion zur Erstellung von Korpora zu digitalen Spielen

*Adrian Demleitner, University of Bern, FS 2023<br>**Einführung in die Digital Humanities***

## Abstrakt
Dieses Teilprojekt im angewandten Teil meiner Dissertation geht praxisorientiert der Fragestellung nach, wie ein Korpus zur Forschung an der Visualität von alten digitalen Spielen aufgebaut werden muss. Damit einhergehen Fragen danach, wie ein Korpus der zu erforschenden Spiele erstellt und strukturiert werden kann. Im Folgenden möchte ich über die Vor- und Nachteile sowie die Implikationen der Anwendung von Ansätzen aus den Digital Humanities reflektieren.

## Forschungsdesign und -methodik
In meiner Dissertation möchte ich zwei Quellenbestände studieren. Die beiden Korpora bestehen aus dem Bildmaterial oder die Visualität von digitalen Spielen sowie deren Quellcode. Für dieses Unterprojekt meines Vorhabens gehe ich auf die Liste der zu untersuchenden Spiele als eigenen Korpus, sowie den Bildkorpus ein. Die Korpusbildung zum Quellcode der Spiele wird in der anschliessenden Diskussion angerissen.

Um meinen Bildkorpus aufzubauen, verfolge ich das Prinzip des Spielens als Forschungsmethode sowie den "Assembling Auras" Ansatz von Guay Belanger. In vielen Fällen produziere ich dabei eigenes Bildmaterials, unter anderem Screenshots von ausgewählten Situationen im Spiel. Da Spiele ungleich einem Film eine gewisse Varianz in sich tragen, sowie die Schwierigkeit besteht, dass alte Spiele nur schwer akkurat wiedergegeben werden können, geht es in Belangers Ansatz darum, möglichst viel und diverses Bildmaterial zu einem Spiel zu sammeln. Dabei bin ich auf Online-Quellen wie spezialisierte Datenbanken oder Webseiten angewiesen.

Um diesen Quellen strukturiert nachzugehen, habe ich mich entschieden, den Schweiz-Anteil der DACH-Liste für Wikidata aufzubereiten. Wikidata ist laut Jean-Frederic Berthelot nicht eine Datenbank, um alle Datenbank zu ersetzen, sondern um diese untereinander zu verknüpfen. Dieser Ansatz kommt meinem Bedürfnis nach vielen verschiedenen Quellen nach.

Die FAIR und CARE Prinzipien waren ein weiterer Grund, warum ich mich für Wikidata entschieden hatte. Durch die Veröffentlichung der kollaborativen Arbeit an der Spiele-Datenbank kann ich sicherstellen, dass die Daten nachhaltig und frei verfügbar abgelegt sind. Wikidata ist nicht zwingend führend, wenn es um die Suche nach Datensätzen geht, jedoch kann dieses Problem mit vorbereiteten Suchanfragen relativ gut angegangen werden.

Ein wichtiges Werkzeug in der Arbeit mit Wikidata ist OpenRefine[^1]. OpenRefine ermöglicht Datenbereinigung und -umwandlung, oder was allgemein unter Data Wrangling verstanden wird. Die Grundlage der Arbeit in OpenRefine sind Daten in Tabellenform, also zum Beispiel Excel Dateien oder, wie in unserem Fall, die kollaborativ generierte Spiele-Liste in einem Google Sheets. Das Werkzeug ermöglicht relativ einfaches Abgleichen mit Wikidata, den Aufbau von Datenmodellen, und schlussendlich auch den Import der bereinigten Daten nach Wikidata.

## Implikationen und Probleme
### Aufwände
Als Erstes möchte ich auf die schwierigen Aspekte eingehen, welche ich in dieser Arbeit angetroffen haben. Grob umrissen wären das die Aufwände, die Standardisierung von komplexen Objekten, Zugänglichkeit zu den Objekten sowie die Qualität der Metadaten.

Die Erstellung eines Korpus kann sehr viel Aufwand bedeuten und ist rein theoretisch nie wirklich abgeschlossen. Das kann im Falle der Absenz einer Forschungsfrage negative Auswirkungen haben, da die zu sammelnden Daten eher unspezifisch definiert sind. Ich hatte mich daher fest an das Forschungsinteresse von Confoederatio Ludens gehalten: Schweizerische digitale Spiele bis und mit dem Jahr 2000.

In meinem Falle hatte ich weniger Arbeit am Metadaten-Model selbst, da dieses grösstenteils von Wikidata als Empfehlung vorgegeben wird. Die Vorgaben hatten für mein Anliegen als Erstes gereicht und einen sicheren Rahmen gebildet. Sehr viel Aufwand hatte vor allem die Akquirierung der Metadaten selbst generiert, also das Durchforsten verschiedener Datenbanken für die Erstellung der initialen Liste. Je nach Plattform ist der Fokus und die Vollständigkeit eine andere. Manche Spiele-Datenbanken führen auch andere Listen für gewisse Attribute, wie zum Beispiel Genre. Hier mussten erste Entscheidungen gemacht werden, wer nun die Deutungshoheit bekommt.

Da wir an Schweizer Spielen interessiert sind und diese Auszeichnung durchaus auch an den Akteuren wie Entwickler:innen, Game Studios und Publisher ausmachen, musste immer wieder auch die Biografie eines Akteurs erforscht werden. Wo hatte diese gelebt oder in welchem Land war das Unternehmen registriert? Dieses Wissen ist oft nicht in den Datenbanken enthalten und musste sehr mühselig in den Weiten des Netzes gesucht werden. Im besten Falle hatten persönliche Webseiten der einzelnen Akteure weitergeholfen.

Zuletzt hatten auch die technischen Umstände Aufwände generiert. Der Prozess der Wikidata Model Bildung, der Abgleichung des eigenen mit dem Wikidata Bestand sowie der Import waren nicht intuitiv. Ich konnte mir das nötige Wissen aber dank einer aktiven Community rund um Wikidata und OpenRefine relativ rasch aneignen. Bei einem Import der Referenzen der einzelnen Spiele auf anderen Datenbank kam es zu gröberen Problemen, welche ich mithilfe einer kleinen Community in einer Telegram-Gruppe zu OpenRefine und Wikidata beheben konnte.

### Standardisierung und Zugang
Trotz der vielen Aufwände ist das Endergebnis relativ bescheiden. Auch wenn sehr viel Arbeit in den Korpus der Schweizerischen digitalen Spiele geflossen ist, umfasst dieser nur einen kleinen Teilbereich der möglichen Attribute und Informationen. Die Standardisierung der Attribute durch das Metadaten-Model bedeutet auch eine Reduktion des erfassten Objektes, welches im Fall von digitalen Spielen sehr komplex sein kann. Im schlimmsten Fall sind für zukünftige Forschungsfragen wichtige Attribute und Beziehungen nicht vorhanden. Ich hoffe diesem Manko durch die FAIR Prinzipien sowie der Veröffentlichung auf Wikidata entgegenzuwirken. Erste positive Ereignisse bezüglich Kollaboration scheinen den Ansatz zu bestätigen.

Weiter sind Metadaten lediglich Indikatoren. Sie können das Forschungsobjekt nur grob beschreiben. Im besten Falle weist ein Eintrag dann auch noch den Weg zum Objekt, zum Beispiel in welcher Sammlung oder welchem Archiv es sich befindet. So könnte eine forschende Person sich aufmachen, und sich das Objekt selbst genauer ansehen. Im Falle von alten digitalen Spielen stehen wir hier noch ganz am Anfang. Es gibt keine Garantie für eine Zugänglichkeit zum Spiel selbst, zum Quellcode des Spieles und zu guter Letzt und für mich spezifisch wichtig, zum Bildmaterial des Spieles. Es sind weltweite und lokale Bestrebungen im Gange, digitale Spiele zu archivieren. Das bedeutet aber auch, dass es keine verlässlichen Standards gibt, welche sich schon durchgesetzt haben. Es gibt noch keine verlässlichen Zeiger, welche ein Korpus-Eintrag aufnehmen könnte, wie und wo der Zugang zu einem Spiel gewährleistet ist.

### Qualität der Metadaten
Zu guter Letzt möchte ich noch die Qualität der Metadaten ansprechen. Bis in jüngster Vergangenheit war die Sammlung von Wissen und Informationen zu digitalen Spielen vor allem eine Hobbyisten-Angelegenheit. Vor allem in der Retro-Szene sind dutzende von Plattformen entstanden, die sich verschiedenen Ansätzen widmen. Manche möchten sämtliche Spiele erfassen, die jemals erschienen sind. Andere konzentrieren sich auf ein einzelnes System, unter anderem den Amiga oder den Commodore 64.

Spannend war ein Gespräch mit Alessandro Adamou von der Bibliotheca Hertziana des Max Planck Institut für Kunstgeschichte. Er konnte mir die Einsicht gewähren, dass Mobygames, eine der grössten und umfassendsten Plattformen, Gamification als Motivationstreiber einsetzt. So bekommen Teilnehmende für verschiedene erfasste Attribute mehr oder weniger Punkte. Akteure seien zum Beispiel besonders wertvoll, weshalb Mobygames auch den besten Datenbestand in diesem Bereich hat.

Jedoch stellen sich bei den Ansätzen Hobby und Gamification schwierige Fragen zur Wissenschaftlichkeit der Datenbestände. Woher kommen die Informationen? Ist es mir möglich, deren Provenienz zu überprüfen? Wurde einfach von einer anderen Plattform kopiert? Wenn ich weder auf Spiele noch deren paratextuelles Material wie Verpackung zurückgreifen kann, bleibt mir oft nicht viel übrig als dem Datenbestand zu vertrauen. Hier helfen Plattformen, welche auch Scans von Verpackung und Anleitungen publizieren. Diese sind in der Regel die verlässlichsten Quellen für Fakten zu einem Spiel.

## Positive Aspekte
Nebst all den schwierigen Aspekten gab und gibt es natürlich auch Positives zu berichten. Hier wären das Potenzial von Wikidata, die Wichtigkeit der Grundlagenarbeit sowie die Forschungs-Community zu nennen.

Jean-Frederic Berthelot hatte in einem Blogpost die These aufgestellt, dass Wikidata nicht andere Datenbanken ersetzen möchte, sondern diese untereinander verknüpfen. Er hatte dazu die Metapher des Pilzmyzel eines Waldes zu Hilfe genommen. Das Myzel verbindet unterirdisch die Bäume miteinander und lässt diese Nährstoffe und Informationen austauschen. Ich hatte die Arbeit am Spiele-Korpus und dessen Import auf Wikidata ähnlich wahrgenommen als Arbeit und Vorbereitung des Bodens, ähnlich wie bei der Gartenarbeit.

Die Aufarbeitung und Veröffentlichung des Korpus unter den Aspekten Open Data, Linked Data und den FAIR Prinzipien ermöglicht mir und anderen Forschenden erst in die eigenen Projekte und Fragen einzusteigen. Unsere DACH-Liste, deren CH Anteil nun auf Wikidata liegt, enthält Wissen, welches vorher in dieser Weise noch nicht konstituiert wurde. Das Feedback auf die Veröffentlichung der Liste war dann auch ausschliesslich positiv. Besonders das Potenzial der Beschreibung von Beziehungen, und nicht nur des Objektes selbst, war mir Anfangs nicht bewusst. Die Beziehung zwischen Spiel und Akteuren ist ein zentraler Bestandteil der Forschung innerhalb von Confoederatio Ludens. Die Aufarbeitung der Akteure und die Erfassung dieser auf Wikidata wird es uns ermöglichen, gewisse rudimentäre Fragen zur Interaktion zwischen den Akteuren zu beantworten und zu visualisieren. Wer hat mit wem zusammengearbeitet? Wie haben sich die Netzwerke zu Austausch und Kollaboration im Laufe der Zeit verändert?

In meiner eigenen Dissertation erhoffe ich mir, dass diese Geflechte später Antworten zu Fragen bezüglich der Visualität der Spiele und anderen Attributen liefern wird. Wie war die Bildkomposition oder ein anderer formaler Aspekt der Spiele in Beziehung zu  den verschiedenen Spielsystemen? Welcher Akteur hat an welchen Spiele-Genres mitgewirkt? Lässt sich daraus ein gewisser Einfluss von bestimmten popkulturellen Strömungen erkennen?

Als letzten Punkt möchte ich auf die erfreuliche Zusammenarbeit mit der Community eingehen. Hier ist im besonderen Jean-Frederic Berthelot zu nennen, welcher mir früh und aktiv zur Seite gestanden ist. Mein Betreuer Eugen Pfister hatten den Kontakt zwischen uns hergestellt. Berthelot ist seit langem Mitglied beim Wikidata Video Games Project und setzt sich da unter anderem aktiv für und mit dem Metadaten-Model auseinander. Nach einem ersten Import meiner Spiele-Liste, welche einige faktuelle Attribute wie Titel und Jahr enthielten, hatte Berthelot gleich erste Referenzen zu anderen Spiele-Datenbanken erfasst und somit Mehrwert für meine eigene Arbeit sowie Confoederatio Ludens generiert.

## Vorschau Arbeit an Bildkorpus
Durch die Auseinandersetzungen mit Theorie und Praxis im Einführungskurs zu den Digital Humanities wurde mir bewusst, wie wichtig die Standardisierung von Daten für die Verarbeitung und Erforschung durch computergestützte Forschung ist. Die Bestätigung dazu kam im persönlichen Gespräch mit meinem Betreuer Tobias Hodel, welcher mir nahegelegt hatte, mir zu überlegen, nach welchen Kriterien ich den Bildkorpus aufbauen möchte.

Ich habe mir dazu folgendes überlegt. Der Bildkorpus wird nach einer Strategie aufgebaut, so viel Material wie nötig aufzunehmen, um Ästhetik und Inhalt eines Spieles so vollständig wie möglich zu repräsentieren. Neben den formalen Elementen und dem visuellen Inhalt, kann das FAVR-Modell zur Kategorisierung der Visualität eines digitalen Spieles helfen, das richtige Material zu finden. Wo möglich, möchte ich dieses Material selbst produzieren, um eine möglichst gute Qualität der Bilder zu ermöglichen. Viele Plattformen haben Screenshots veröffentlicht, jedoch sind diese zufällig gewählt und oft von niederer Qualität, zum Beispiel durch Kompressionsartefakte, Beschneidungen des Bildes oder Veränderungen des Farbeschema durch Formats-Konvertierungen.

Ich habe dazu drei Bereiche definiert, welche für mich wichtig sind. Diese umfassen formale Elemente, Inhalt sowie dem Framework for the Analysis of Visual Repräsentation in Video Games, zur kurz FAVR.

- Formale Elemente: Farbschema, Typografie, Komposition etc.
- Inhalt: Level, Sprites (Objekte), Spielcharaktere etc.
- FAVR: Visuelle Modi, Okularisierungen, Rahmungsmechanismen, Konstruktion des greifbaren Raums; diese werden durch das FAVR vorgegeben

FAVR ist ein Versuch, ein eigenes Vokabular zur Beschreibung des Bildes im Spiel zu definieren. Dieses Vokabular entstammte bis anhin vor allem der Kunsttheorie zum Bild sowie der Medientheorie rund um den Film. Das ist zwar intuitiv, vermag es aber nicht, das Spezifische im Bild des digitalen Spieles zu erfassen.

Das Bildmaterial wird andere Ansprüche an den Korpus stellen, als Metadaten das tun, müssen jedoch im Zusammenhang zu diesen gedacht werden. Ich möchte deshalb auf Tropy und Omeka setzen. Tropy ermöglich die qualitative Forschung am Bild, wie zum Beispiel die Verschlagwortung und Annotation, und setzt dazu fest auf die Arbeit mit Metadatenmodellen. Ich kann also meinen Rahmen zur Sammlung des Bildmaterials direkt in ein Model übersetzen und dieses den Einzelobjekten zuweisen und befüllen. Tropy ermöglicht den einfachen Import nach Omeka, womit Archivierung und Publikation von Bildmaterial und Metadaten ebenfalls leicht zu bewältigen wären.

## Diskussion
Die Arbeit am Korpus hat mir geholfen, mein Forschungsmaterial, dessen Zustand und Möglichkeiten zu reflektieren. Die Richtung war mir bekannt, es geht um das Bild im digitalen Spiel. Da jedoch weder ausführliche Metadaten noch Bildmaterial vorhanden waren, ist es relativ schwierig, die Forschungsfragen darauf auszurichten. Die Rahmung, welche Metadatenmodelle mit sich bringen sind zwar limitierend, jedoch gibt es im Design die Grundregel, dass eine Rahmung auch die Freiheit mit sich bringt diese zu sprengen. Die Rahmung der Metadaten weist durch die Reibung an ihr auf fehlende und fehlerhafte Information hin, und wo eine genauere Auseinandersetzung, sprich Forschung, nötig ist. So sind etwa die Attribute *genre* oder *place of origin* im Wikidata Video Game Model im spezifischen aufgefallen, da sich diese nicht so einfach bestimmen liessen. Zuletzt war die Arbeit am Spiele-Korpus auch richtungsweisend für das Design des Bild-Korpus, wie oben schon ausgeführt.

Die Auseinandersetzung hat mir auch direkt die Vorteile und Schwächen der Ansätze in den Digital Humanities aufgezeigt, vor allem in Bezug auf die Limitation der Forschungsobjekte, aber auch der Aufwände, die so eine Aktivität mit sich bringt. Besonders positiv ist mir hier das Potenzial von Kollaborationen und der Wert von FAIR/CARE aufgefallen. FAIR/CARE ermöglicht nicht nur ethisch korrekte Forschungsdaten, sondern helfen auch in der gemeinsamen wissenschaftlichen Arbeit und der Qualitätssicherung der Daten. Diesbezüglich ist in mir der Wunsch aufgekommen, das digitale Archiv swissgames.garden, mit welchem Confoederatio Ludens hauptsächlich arbeitet, in Richtung Open Data zu erweitern. Ich könnte mir vorstellen, dass der einfache Download von Datensätzen und die Verlinkung zu Wikidata schon sehr viel Mehrwert in diesem Bereich bringen könnte.

Abschliessen möchte ich mit dem Hinweis, dass es nebst Spiele-Liste und Bildmaterial noch einen dritten Korpus zu erstellen gilt. Da ich in meiner Dissertation auch eine kritische Code-Analyse vornehmen möchte, brauche ich Zugriff zum Quellcode der Spiele. Auf die Schwierigkeiten bezüglich Zugang zu Spielen und Quellcode bin ich schon eingegangen. Jedoch gesellen sich hier bezüglich der Korpusbildung noch weitere Probleme dazu, welche ich für den Moment nicht weiter ausführen möchte. Zu erwähnen sind sicherlich das Auffinden und die Langzeit-Archivierung des Quellcodes. Auch wenn die Schwierigkeit andere sein werden, fühle ich mich durch die Auseinandersetzung mit den Grundlagen der Digital Humanities sowie der Arbeit an den ersten beiden Korpora gut vorbereitet. 

## Bibliography
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