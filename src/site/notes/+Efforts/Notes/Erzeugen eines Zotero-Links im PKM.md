---
{"dg-publish":true,"permalink":"/efforts/notes/erzeugen-eines-zotero-links-im-pkm/","tags":["class/note","class/outcome"],"dg-note-properties":{"tags":["class/note","class/outcome"],"created":"2025-02-01","up":["[[Wie ich Zotero mit Obsidian verwende]]"],"related":null,"gg-pkm-class":["000 Informations- und Wissensmanagement","009a PKM","040 Methoden, Arbeitsweisen"]}}
---


### Purpose
Zielsetzung dieses Beitrags ist es zu erläutern, wie ich in meinem PKM System **Links zu Zotero-Datenbank-Einträgen** erzeuge.
Hintergrund des Ganzen ist, dass solche Links an vielerlei Stellen in einem PKM-System sinnvoll platziert werden können, ich dies insbesondere aber in meinem täglichen Logbuch anstrebe zu tun: 
- Ich finde es wertvoll die Tatsache der Erstellung eines Zotero-Eintrags festzuhalten und dabei den Link zum Eintrag zu verwenden. 
- Ich finde es ebenso wertvoll im täglichen Log zu vermerken, wenn ich mich mit einem Werk (Buch, Artikel etc.), das im Zotero gespeichert ist,  auseinandergesetzt habe dies zu vermerken. Auch dabei ist ein Link zum Zotero-Eintrag wertvoller als die Information als reiner notierter Text.

### Inhaltliche Voraussetzung 
Der Zotero-DB-Eintrag muss existieren.[^1]
Ich arbeite diesbezüglich so, dass ich immer dann, wenn ich bei einer **InternetRecherche** an einem gesuchten (oder zufällig gefundenen) Werk vorbei komme, dieses per BrowserPlugin der Zotero-Bibliothek hinzufüge. Damit existiert es. in der Zotero DB.

### Einbettung in meine Routinen
In meiner täglichen Rückschau auf meinen Tag notiere ich, was ich an diesem Tag geschafft, gedacht, erreicht oder nicht erreicht habe. Ein Teil des Erreichten ist die Erweiterung der Zotero-DB um einen (oder mehrere) Beiträge.

### Setzen des Links zum Zotero-Eintrag
#### (technische) Voraussetzung im PKM System (hier: Obsidian)
Zum alleinigen Setzen eines Links in die Zotero DB verwende ich das Obsidian Community Plugin "[Zotero Link](https://github.com/vanakat/zotero-link)", welches allerdings das Obsidian Community Plugin "[Zotero Bridge](https://github.com/vanakat/zotero-bridge)" voraussetzt.
##### Einstellung Zotero Bridge
Gemäß meiner Zotero-Version muss die Einstellung des Plugins wie folgt aussehen
![Settings in Zotero Bridge.png](/img/user/+References/Images/Settings%20in%20Zotero%20Bridge.png)wobei im Feld "User or Group" die als Quelle zu verwendende Zotero Bibliothek anzugeben ist.[^2]
##### Einstellung Zotero Link
Ich möchte den Link zum Zotero Eintrag nachdem Pattern `{firstAUTHOR.LASTNAME} [YEAR) - {TITLE}` erstellt bekommen. Ergo gebe ich im einzig einzustellenden Feld folgenden "Code" ein:
- {{ firstAuthor.lastName }} ({{ date.year }}) - {{ title }}

##### Befehl zum Setzen des Links
Für das Werk "The Product Book" ergibt sich dann bei Ausführung des Befehls "Zotero Link: Insert" der Link[^3] und ich bin in der Lage im Täglichen Log zum Beispiel folgendes zu notieren:
- LOGGING:: Ich habe heute ein weiteres Kapitel im Buch [Anon (2017) - The Product Book](zotero://select/library/items/DVLFJ4W9)[^4] gelesen, und frage mich ernsthaft, was in diesem Buch ... (das verrate ich hier nicht 😉) ...

### Fazit
Es sollte klar geworden sein, wie ein reiner Link zu einem Zotero-Eintrag in einem auf Obsidian basierenden PKM-System (**an beliebiger Stelle im PKM-System**) gesetzt werden kann. Man benötigt lediglich (neben Zotero) die Obsidian Community Plugins "[Zotero Bridge](https://github.com/vanakat/zotero-bridge)" & "[Zotero Link](https://github.com/vanakat/zotero-link)".




[^1]: Dass für diese **inhaltliche** Voraussetzung auch die **technische** Voraussetzung "Zotero muss im Einsatz sein" existert, beleuchte ich mal nicht weiter im Detail. 😉

[^2]: ich habe im Bild die Bezeichnung meiner Bibliothek ausgeblendet.

[^3]: Ich habe mir übrigens für schnelleres (mausfreies) Arbeiten im PKM das Tastenkürzel `ALT + Z` auf den Befehl "Zotero Link: Insert" gelegt.

[^4]: Dass die meisten Leser von https://knowledge-garden.de mit dem hier publizierten Link ins vollkommen Leere greifen und jene, bei denen Zotero installiert ist, nichts finden, sollte niemanden verwundern. Denn natürlich greift der Link auf die *lokale* Anwendung Zotero zu und nicht auf jene Zotero-Anwendung des Autors dieser Notiz. Falls jemand etwas findet, in seinem eigenen Zotero, dann liegt es am zufällig dort ebenfalls vorhandenen Datenbankeintrag "DVLFJ4W9", der aber natürlich nicht von "The Product Book" belegt sein dürfte. 🤣🤣🤣🤣
