---
{"dg-publish":true,"permalink":"/efforts/notes/aufgaben-automation-und-management-fuer-blogger-innen/","tags":["class/outcome"]}
---


# Die Challenge
**Ausgangspunkt**
Die Blogger:in möchte über die Bücher bloggen, die gelesen werden.
Dazu stehen Aufgaben an, die für jedes gelesenen Buch identisch sind. Eine Feste Aufgabenliste für jedes Buch. Die Variable ist einzig und allein das nächste Buch, welches für den Blog zu verarbeiten ist.

**Kern der Herausforderung**
Verwalte diese Aufgaben auf einen Blick mittels [Obsidian](https://obsidian.md)

**technische Hinweise / Prämissen**
- Obsidian Version 1.11.7 ist die Version, mit der wir arbeiten
- Wir nutzen die Community PlugIns [Templater](https://obsidian.md/plugins?id=templater-obsidian) und [Tasks](https://obsidian.md/plugins?id=obsidian-tasks-plugin) 
- Wir verwalten unsere Templates in einem separierten Folder "Templates"

# Die Lösungsidee
- **Ein Aufgabenlisten-Template**: Wir bauen uns ein Template mit einer fertigen immer gleichen Aufgabenliste. Jedes zu verarbeitende Buch wird als Buch-Aufgaben-Liste im Vault mittels dieses Templates verwaltet.
- **Aufgabenlisten-Insel**: Wir verwalten die buchspezifischen Aufgabenlisten in einem eigens dafür vorgesehenen Folder innerhalb unseres Vaults. Alle Buch-Aufgaben-Listen werden in diesem Folder (der Insel) gespeichert.
	- der Hintergedanke ist hier, diese Dateien sind für den Rest des Vaults, der ja ein Zettelkasten oder ein zweites Gehirn ist, nach ihrer Abarbeitung ohnehin unerheblich.
- **Eine MapOfContent für die Challenge**: Um den **einen** Überblick zu haben lassen wir uns in einer MapOfContent an beliebig zentraler Stelle im Vault die noch offenen (und nur diese) Aufgaben-Listen anzeigen.

# Die Umsetzung ganz konkret
- Wir erzeugen uns ein **File-Template** mit der (für jedes Buch identischen sequentiell abzuarbeitenden) Aufgabenliste. 
	
<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">





- [ ] #task BOOK BLOGGING TASK 1 ➕ 2026-02-13
- [ ] #task BOOK BLOGGING TASK 2 ➕ 2026-02-13
- [ ] #task BOOK BLOGGING TASK 3 ➕ 2026-02-13




</div></div>


- Wenn wir über ein Buch bloggen wollen, erzeugen wir **buchspezifische Aufgabenlisten-Files** im Vault auf Basis dieses Templates und wir speichern dieses File **in der Aufgabenlisten-Insel**. In Unserem Beispiel ist das der Ordner "+Efforts/Learnings"
	- um mal darzustellen, wie diese Files auf der Basis unseres beispielhaften Filetemplates tatsächlich aussehen, wenn sie denn erzeugt wurden, verlinke ich hier mal zwei Beispiele
		- [[+Efforts/Learnings/Buch XYZ\|Buch XYZ]]
		- [[+Efforts/Learnings/Buch ABC\|Buch ABC]]

- Wir erzeugen *an beliebiger zentraler Stelle* im Vault eine **Map of Content** mit dem **Überblick über die offenen Aufgaben aus der Aufgabenlisten-Insel*
	- in unserem Fall ist die zentrale Stelle der Ordner "+Atlas/INDIZEES"
	- Und man kann sich das Ergebnis hier anschauen: [[+Atlas/INDIZEES/MOC Blogging Task-Listen\|MOC Blogging Task-Listen]]


> [!COMPASS] Mehr Orientierung?
> Frage gerne nach per E-Mail, in dem Du das Formular https://letterbird.co/gerald-g ausfüllst und auf diese Seite hier Bezug nimmst.  




