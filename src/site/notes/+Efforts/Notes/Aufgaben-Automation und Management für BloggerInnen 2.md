---
{"dg-publish":true,"permalink":"/efforts/notes/aufgaben-automation-und-management-fuer-blogger-innen-2/","tags":["class/outcome"]}
---

siehe [[+Efforts/Notes/Aufgaben-Automation und Management für BloggerInnen\|Aufgaben-Automation und Management für BloggerInnen]]
# Die neue Challenge
**Ausgangspunkt**
Die Blogger:in möchte - wie in [[+Efforts/Notes/Aufgaben-Automation und Management für BloggerInnen\|Aufgaben-Automation und Management für BloggerInnen]] dargelegt - über die Bücher bloggen, die gelesen werden.
Dazu stehen Aufgaben an, die für jedes gelesenen Buch identisch sind. Eine Feste Aufgabenliste für jedes Buch. Die Variable ist einzig und allein das nächste Buch, welches für den Blog zu verarbeiten ist.

**Kern der Herausforderung**
Verwalte diese Aufgaben auf einen Blick mittels [Obsidian](https://obsidian.md) aber ermögliche insbesondere den Blick aus der Perspektive der einzelnen Aufgaben.

**technische Hinweise / Prämissen**
- Obsidian Version 1.11.7 ist die Version, mit der wir arbeiten
- Wir nutzen die Community PlugIns [Templater](https://obsidian.md/plugins?id=templater-obsidian) und [Tasks](https://obsidian.md/plugins?id=obsidian-tasks-plugin) 
- Wir verwalten unsere Templates in einem separierten Folder "Templates"
- Wir müssen für die Besonderheit der Challenge die File-Properties verwenden

# Die Lösungsidee
- **Ein Aufgabenlisten-Template**: Wir bauen uns ein Template mit einer fertigen immer gleichen Aufgabenliste ==innerhalb der File-Properties==. Jedes zu verarbeitende Buch wird im Vault mittels dieses Templates verwaltet. Das Template sorgt dafür, dass wir eine Aufgabenliste in den File-Properties finden, mit der Default-Einstellung `false` je "Aktivitäts-Property" 
- **Aufgabenlisten-Insel**: Wir verwalten die buchspezifischen Aufgabenlisten in einem eigens dafür vorgesehenen Folder innerhalb unseres Vaults. Alle Buch-Aufgaben-Listen werden in diesem Folder (der Insel) gespeichert.
	- der Hintergedanke ist hier, diese Dateien sind für den Rest des Vaults, der ja ein Zettelkasten oder ein zweites Gehirn ist, nach ihrer Abarbeitung ohnehin unerheblich.
	- Die Pflege der Files beschränkt sich auf die Pflege der Aktivitäts-Properties
- **Eine MapOfContent für die Challenge**: Um den **einen** Überblick zu haben lassen wir uns in einer MapOfContent an beliebig zentraler Stelle im Vault die gemäß Aktivitäts-Property offenen Files auflistet (bei denen die jeweils abgefragte Eigenschaft ``false`` ist)

# Die Umsetzung ganz konkret
- Wir erzeugen uns ein **File-Template** mit der (für jedes Buch identischen sequentiell abzuarbeitenden) Aufgabenliste in den Properties. 
	![Properties gemäß Template.png](/img/user/+/Properties%20gem%C3%A4%C3%9F%20Template.png) 

- Wenn wir über ein Buch bloggen wollen, erzeugen wir **buchspezifische Aufgabenlisten-Files** im Vault auf Basis dieses Templates und wir speichern dieses File **in der Aufgabenlisten-Insel**. In Unserem Beispiel ist das der Ordner "+Efforts/Learnings"
	- um mal darzustellen, wie diese Files auf der Basis unseres beispielhaften Filetemplates tatsächlich aussehen, wenn sie denn erzeugt wurden, verlinke ich hier mal zwei Beispiele
		- [[+Efforts/Learnings/Book DEF\|Book DEF]] 
		- [[+Efforts/Learnings/Book UVW\|Book UVW]] 

- Wir erzeugen *an beliebiger zentraler Stelle* im Vault eine **Map of Content** mit dem **Überblick über die offenen Aufgaben aus der Aufgabenlisten-Insel*
	- in unserem Fall ist die zentrale Stelle der Ordner "+Atlas/INDIZEES"
	- Und man kann sich das Ergebnis hier anschauen: [[+Atlas/INDIZEES/MOC Blogging Task-Listen mit Aktivitäts-Fokus\|MOC Blogging Task-Listen mit Aktivitäts-Fokus]]


> [!COMPASS] Mehr Orientierung?
> Frage gerne nach per E-Mail, in dem Du das Formular https://letterbird.co/gerald-g ausfüllst und auf diese Seite hier Bezug nimmst.  




