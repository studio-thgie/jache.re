---
created: 2023-09-18T11:42
updated: 2023-09-25T11:53
---
# Das PTT-Archiv im Zeitalter von Linked Open Data
- [ILIAS](https://ilias.unibe.ch/goto_ilias3_unibe_crs_2760077.html) & [KSL](https://www.ksl.unibe.ch/KSL/kurzansicht?3&stammNr=484302&semester=HS2023&lfdNr=0)
- [Journal](#journal)

## Journal
## 2023-09-25
- Textbesprechung von [Mein Computer versteht mich](reading/hypothes.is/Internet%20Mein%20Computer%20versteht%20mich.md)
	- Wie versteht Lee semantisches Netz?
	- Unterschiede zum WWW?
	- Probleme und Herausforderungen:
		- Semantisches Web ist ein "academic pipe-dream"
		- Sicherheitsbedenken
		- Sich auf eine saubere Modellierung zu einigen; RDF ist nur ein technischer Standard
		- Moderation und Info-Produktion; wer darf eigentlich wie diese Ontologien bauen
- Wikidata und SPARQL
	- SPARQL Queries im Details besprochen, sozusagen als Refresher. Was macht einen einfachen und komplexeren Query aus. Im folgenden ein Query welcher nach Poststellen im PTT Archiv sucht

```sparql
SELECT DISTINCT ?item ?itemLabel ?itemDescription ?sitelinks
WHERE {
    # ?item wdt:P31 wd:Q679206;
    #      wdt:P17 wd:Q39.
  
    # ?item wdt:P749 wd:Q1307956;
    
    ?item wdt:P31 wd:Q35054;
          wdt:P17 wd:Q39;
          wdt:P485 wd:Q16964584.
   
    SERVICE wikibase:label { bd:serviceParam wikibase:language "[AUTO_LANGUAGE],en" }
}
ORDER BY DESC(?sitelinks)
```

- [Poststellen im PTT Archiv)](https://w.wiki/7YiW)

### 2023-09-18
- Kaum Notizen heute, es geht vor allem um die Einführung und Organisatorisches.
- Erwähnt wurden die [FAIR and CARE principles](notes/FAIR%20and%20CARE%20principles.md), welche wir in der Einführung schon im Detail durchgegangen sind. Mehr dazu auch [in meinem Kurs Journal](https://github.com/DHBern/einf_2023/blob/main/ftb_Adrian_Demleitner/index.md) und der [Reflexion zum Kurs Projekt](https://github.com/DHBern/einf_2023/blob/main/ftb_Adrian_Demleitner/projektreflexion.md).
- Im Spiel Züri (1991) hat es ein paar Referenzen zur PTT :)
  ![](assets/Screenshot%202023-09-18%20at%2011.40.09.png)
  