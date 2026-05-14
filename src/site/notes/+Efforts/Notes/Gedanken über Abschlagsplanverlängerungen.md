---
{"dg-publish":true,"permalink":"/efforts/notes/gedanken-ueber-abschlagsplanverlaengerungen/","tags":["class/outcome"]}
---


# Abschlagplanverlängerungen und welche Wirkung sie entfalten

## Ausgangspunkt
Vor einiger Zeit sprach man sich bei einem mir bekannten Energieversorger dafür aus, bestehende Abschlagpläne - prophylaktisch - zu verlängern, weil man befürchtete, die regulären Arbeiten zur Jahresverbrauchsabrechnung (JVA) irgendwie nicht zeitgerecht zu schaffen.

Wenn man als Energie-Lieferant die Jahresverbrauchsabrechnung nicht pünktlich abwickelt läuft man Gefahr in ein Cash-Flow-Problem zu laufen, weil ohne Abrechnungen/Fakturierungen des gerade vergangenen und zur Abrechnung anstehenden Zeitraums keine Forderungen erhoben werden uns somit auch kein Kunde Zahlungen anweist und auch im Einzugsverfahren schlicht die Grundlage für den Geldeinzug von den Kunden-Bankkonten fehlt.
Die Formel ist einfach: Keine Abrechnung - keine Forderung - kein Geldeingang.
Und diese Formel ist unbestreitbar richtig!

### Exkurs Rollierung oder Stichtag
Es gibt Versorger, die mittels einer sogenannten rollierenden Abrechnung den Kundenbestand über das Jahr terminlich verteilt in (in etwa gleichgroße) Abrechnungsportionen zerlegen. Diese Versorger machen das ganze Jahr über regelmäßig wiederkehrend JVA. Sie haben keine Spitzenlast im Jahr, was die JVA betrifft.
Die für Abrechnung zuständige Org-Einheit ist kontinuierlich mit derselben Aufgabe ausgelastet. Weil es dieselbe Aufgabe ist, ist die Organisation inhaltlich auch kaum überfordert. 
Der Unternehmens-Cash-Flow fließt kontinuierlich über das Kalenderjahr verteilt.

Anders sind Versorger organisiert, die eine sogenannte Stichtagsabrechnung vornehmen: Alle Kunden zum gleichen Stichtag. Oft der 31.12.! 
Fakt ist hier, die ganze Organisation ist genau einmal im Jahr mit den Aktivitäten der Abrechnung/Fakturierung befasst. Es dürfte kaum Raum für andere Aktivitäten sein, selbst unerwartet Aufkommendes muss liegen bleiben, weil schlicht niemand Zeit dafür hat, denn die JVA muss durchgepeitscht werden, weil sonst kein Geld kommt. 
Der Unternehmens-Cash-Flow hängt an der Stichtagsabrechnung.

## Die Herausforderung
Das Beispielunternehmen sei ein Stichtagsabrechner. Immer über den Jahreswechsel hinweg[^3] heißt es dort: Alle Mann an Deck und in die Seile! 
Im konkreten Fall machte man sich bereits im Oktober Sorgen, ob die nächste JVA denn zeitgerecht durchgebracht werden könne ... 

Nun kam man beim Versorger auf die - zunächst(!) - einleuchtende Idee sich auf eine möglichen Cash-Einbruch durch nicht zeitgerechte JVA in der Art vorzubereiten, in dem man schlicht die bestehenden Abschlagspläne um weitere Fälligkeiten verlängert[^1]. 
Immerhin eine optionale Standard-Funktionalität für die Behandlung von Abschlagsplänen.

Einleuchtend erscheint es, weil durch die Verlängerung des bestehenden Abschlagsplanes um neue Fälligkeiten diese auch einer Beitreibung offen stehen. Das Cash-Flow-Problem erscheint abwendbar. Auf den ersten Blick.

## Zweiter Blick, oder Ende-zu-Ende-Überlegung - Ein Beispiel
Was aber passiert, wenn man als Stichtagsabrechner seine Jahresverbrauchsabrechnung (JVA) in Gänze nicht zu schaffen scheint und ergo sämtliche Abschlagspläne verlängern muss (für jene Kunden, deren JVA man eben nicht zeitgerecht schafft)?

Zunächst einmal werden die Abschlagspläne mit neuen, über die ursprüngliche Abschlagsplanperiode hinausgehende Fälligkeiten ausgestattet. Ein Abschlagsplan mit vormals 12 Fälligkeiten bekommt bspw. drei neue hinzu und erstreckt sich im Ergebnis dann über 15 Fälligkeiten. Die 3 neuen Fälligkeiten werden im System als drei neue Abschlagsplanpositionen geführt.
Das gilt für alle Abschlagspläne im System eines Stichtagsabrechners.

Die neuen Abschlagsfälligkeiten können, sobald sie fällig werden, eingezogen oder selbst vom Kunden bezahlt werden. Alles scheint gut. Der Cash-Flow versiegt nicht. Zunächst nicht!

Doch irgendwann muss man den noch nicht abgerechneten letzten Abrechnungszeitraum zur Abrechnung/Fakturierung bringen. Und hier schlägt "ordnungsgemäße Buchführung" zu.

Naturgemäß liegt der Zeit**punkt** der Abrechnung jetzt genau in einem Zeitraum, der - bezogen auf den jetzt abzurechnenden Zeitraum - der nächste abzurechnende Zeitraum ist, der schon "signifikant vergangen" ist.    (Lies das ruhig noch einmal!)
Dieser Zustand hat Folgen.

Die aktuelle Abrechnung bezieht sich auf das vergangene Kalenderjahr. Der Zeitpunkt der Abrechnung des vergangenen Kalenderjahres liege am 5. April des aktuellen. Ein Viertel des aktuellen Abrechnungsjahres ist also bereits vorüber, während man das vergangene Jahr zur Abrechnung bringt, und der Kunde hat drei aus der Verlängerung des vergangenen Abschlagsplanes resultierende Abschläge bezahlt.
Der Verbrauch des vergangenen Jahres geht in die Abrechnung ein und wird bewertet, die Rechnungssumme für das vergangene Jahr wird ermittelt.
Die zu diesem Zeitpunkt (=5. April) auf dem Kundenkonto verbuchten (15 statt 12) Abschlagszahlungen werden gegen die Rechnungssumme des vergangenen Jahres verrechnet und es wird die Restforderung ermittelt - ein Viertel mehr an Abschlagszahlung (15 statt 12) in der Verrechnung dürfte unter normalen Bedingungen zu einer Gutschrift für den Kunden führen[^2]. 

Im Ergebnis hat man also zunächst den Cash-Flow drei Monate lang gesichert, im vierten Monat aber fließt nun Cash (in Höhe von drei Monaten) ab, weil periodenfremde Abschlagszahlungen in der späten Fakturierung zu im Zweifel enormen Gutschriften führen.

Die Fakturierung des vergangenen Jahres zu einem späten Zeitpunkt (=5. April) erzeugt einen neuen Abschlagsplan für das aktuelle Jahr, dieser bekommt aber, weil der vergangene Abschlagsplan ja bis in den März verlängert worden war, nur die Möglichkeit von April bis Dezember des aktuellen Jahres aufgespannt zu werden, was nur 9 (statt geplanter 12) mögliche Fälligkeiten zulässt.

Unter der modellhaften Annahme, dass beim Kunden keine Verbrauchsverhaltensänderung vorhersehbar ist und auch in der Vergangenheit die Balance zwischen Verbrauch und Abschlagshöhe gewahrt war, hat dies zur Folge, dass der für aktuelle Jahr prognostizierte Verbrauch in nur 9 statt 12 Abschlagsplanpositionen "gepresst werden muss", was die einzelnen Positionen größer macht, als in der Vergangenheit.

Für den Versorger ist das insofern zunächst wieder gut, als er ab dem Einzug der nächsten Abschlagsplanfälligkeit einen leicht erhöhten Cash-Flow verzeichnet. Was aber nicht dazu führen dürfte, den Cash-Abfluss aus den zu erwartenden Gutschriften der gerade vergangenen Jahresverbrauchsabrechnung für das vergangene Jahr mit dem Einzug des ersten neuen Abschlags ausgeglichen zu haben.

In der Außenwirkung wird der erhöhte Abschlagspositionsbetrag den Kunden mehr verärgern, als ihn die nur noch 9 statt 12 Abschlagsfälligkeiten erleichtern, zumal er durch die vorangegangene Verlängerung des alten Abschlages ohnehin den dort benannten Abschlagspositionsbetrag und die zusätzlichen Fälligkeiten erinnert. Dass er zwischendrin eine Rückzahlung bekommen hat, dürfte das Bild für ihn dann bestenfalls mit einem Kopfschütteln bewerten, wenn nicht mit Bauchgrummeln darüber, was sein Versorger da eigentlich tut. 

Ich würde als Kunde Fragen haben und mir Sorgen machen, dass mein Versorger seine innerbetrieblichen Prozesse nicht im Griff hat.  

## Fazit
- Abschlagsplanverlängerungen 
	- scheinen ein Cash-Flow-Problem lösen zu können.
	- Wenn es um Einzelfälle geht, mag die Abschlagsplanverlängerung ein sinnvolles Vorgehen zu sein. 
	- Bei einer den Gesamten Kundenbestand betreffenden nicht zeitgerechten Jahresverbrauchsabrechnung jedoch vertagt sich das Cash-Flow-Problem lediglich im Zeitpunkt dorthin, wo das vergangene Kalenderjahr zur Abrechnung kommt.
	- Darüber hinaus ist die Außenwirkung der Maßnahme für Kunden mindestens geeignet, Zweifel an der Seriosität des Versorgers aufkommen zu lassen.

- Anstelle der Abschlagsplanverlängerung kann als taktische Maßnahme die frühzeitige Erstellung neuer Abschlagspläne für das kommende Abrechnungsjahr ins Auge gefasst werden
	- die Folgen wären gegenüber der Abschlagsplanverlängerung grundsätzlich andere
	- Dazu mehr [hier]


Um der JVA letztlich für immer den Druck zu nehmen, ist eine Umstellung auf rollierende Abrechnung das bessere Instrument - aber das ist ein deutlich strategischerer Ansatz, als eine taktische Maßnahme. 
Dies muss in der Organisationsentwicklung flankiert werden durch die Schaffung einer kleinen, aber feinen, nur für die rollierende Abrechnung verantwortlichen Org-Einheit.


---

[^3]: Ausgerechnet den 31.12. als Stichtag zu wählen erscheint mir persönlich für die betreffenden Organisationen als zusätzliches Belastungsmoment, dem nur ein Argument zugrunde zu liegen scheint: das sei nun mal das Ende des Jahres. Ein stichhaltiges Argument indes sieht anders aus.
[^1]: Inwieweit man sich mit einer - fortgesetzten - Verlängerung von Abschlagsplänen aus dem zulässigen Rechtsrahmen des EnWG entfernt, soll hier nicht Gegenstand sein. 
[^2]: Weil normale Bedingungen bedeutet: Die Höhe der Summe der ursprünglichen 12 Abschläge für 2024 ist optimalerweise in etwa so hoch wir die für 2024 zu erwartende Rechnungssumme. Zusätzliche 3 Abschlagsfälligkeiten in gleichbleibender Höhe neigen zu einer Überzahlung in Bezug zum zu erwartenden Rechnungsbetrag für das Jahr.   
