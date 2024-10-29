---
{"dg-publish":true,"permalink":"/atlas/about-decisions/","tags":["class/note"],"created":"2024-10-29","updated":"2024-10-29T17:39:41.238+01:00"}
---


## Hintergrund
Im beruflichen Alltag (aber nicht nur dort) werden zu allen Zeiten **Entscheidungen** gefällt. Die Herausforderung mit getroffenen Entscheidungen liegen oft darin, diese Entscheidungen zu dokumentieren. Sie zu treffen fällt noch relativ leicht, sie dokumentiert zu haben schon schwerer, und sie dann - oft Wochen oder Monate Später - bei einem plötzlich aufkommenden Bedürfnis nach Nachlesbarkeit auch schnell wieder hervorzuholen, sie wiederzufinden, stellt uns vor noch höherer Herausforderungen.  

## Anforderungen an ein PKM System bezüglich Entscheidungen
In (m)einem PKM-System (und hier geht es wirklich um die *persönliche* KM-Perpektive) kommt also auf drei Dinge an, wenn es um Entscheidungen geht.
1. die Entscheidungen müssen irgendwo im PKM-System erfasst sein - 
	- das scheint trivial, generiert aber insofern Mehr-Arbeit, als berufliche Entscheidungen meist innerhalb der beruflichen Infrastruktur dokumentiert sein müssen, worauf man selbst keinen Einfluss hat. Wenn nun die Erinnerungsstütze an eine solche Entscheidung im PKM System auftauchen soll, muss sie dort mindestens ein zweites Mal erfasst werden. 
2. die Entscheidungen müssen irgendwie im PKM-System *geeignet als Entscheidungen gekennzeichnet* sein, sofern man sie eben ___nicht___ einfach höchst simpel der Reihe nach in eine Notiz mit der Überschrift "Entscheidungen" auflisten will, sondern sie passgenau in jenen Notizen, seien es Projekt-Logbücher, seien es Tage-Bücher etc innerhalb des PKM-Systems unterzubringen gedenkt, in deren Kontext sie aufkamen
3. wenn genau eine simple Liste nicht ausreichend ist, sollte es *zusätzlich* eine ***Verzeichnis-von-Entscheidungen*** geben, welches sich - um nicht noch mehr Mehr-Arbeit zu generieren - von selbst füllt.

## Lösung in (m)einem PKM-System
### Vorbemerkung
Hier ist anzumerken, dass mein PKM-System aus folgenden Bestandteilen besteht:
- Software: [Obsidian](https://obsidian.md) in der jeweils neuesten Version
- vorausgesetztes Plugin für Obsidian: [Dataview](https://github.com/blacksmithgu/obsidian-dataview) 
### Umsetzung
- Entscheidungen erfasse ich innerhalb von Projekt-Logbüchern, Meeting-Notizen oder den Daily Notes in einer einfachen Form innerhalb eines Absatzes der mit `decision::` begonnen wird. Eine [[Beispieldatei für eine Meeting-Note mit einer erfassten Entscheidung\|Beispieldatei für eine Meeting-Note mit einer erfassten Entscheidung]] zeigt das anschaulich.
- Entscheidend ist, dass auf diese Weise, egal in welcher im PKM-System befindlichen Notiz, diese Absätze technisch gesehen durch den `::` zu einem Feld mit dem Namen `decision` werden. Das nutzen wir dann für das automatisiert zu füllende Verzeichnis aller Entscheidungen aus, indem wir das Plugin Dataview seine Künste vollführen lassen.   
- Das Verzeichnis der Entscheidungen - eine separate Notiz - listet mir dann alle Entscheidungen. Wie das Beispielhaft aussehen kann werde ich einem [[MoC Beispiel Entscheidungen\|MoC Beispiel Entscheidungen]] mal ausführlich beschreiben. (coming soon!)
