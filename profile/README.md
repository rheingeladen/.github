# RHEINGELADEN

**Websites für Betriebe am Rhein — von Bonn bis Kleve.**

Gebaut wird nicht jedes Mal von vorn. Unter jeder Kundenseite liegt dasselbe
Blocksystem: geprüfte Bausteine, ein Theme je Kunde, eine Datei für den
Ortsbezug. Was einmal richtig gelöst ist, bleibt richtig gelöst.

---

## Drei Zusagen, die Technik sind — keine Absicht

**Kein Cookie-Banner.** Nicht als Verzicht, sondern weil nichts einwilligungs-
pflichtig ist: keine eingebettete Karte, keine Schrift von einem fremden
Server, kein Cookie. Gezählt wird durchaus — nur ohne Kennung im Browser und
ohne fremden Host, die Messwerte gehen an die eigene Domain. Ein Test bricht
den Build, sobald eine Seite zum ersten Mal irgendwohin nach draußen spricht.

**Barrierefrei, nicht barrierearm.** Jeder Baustein hat seinen eigenen
Zugänglichkeitstest, jede Seite wird zusätzlich als Ganzes geprüft — hell und
dunkel, mit der Maus und nur mit der Tastatur. Farbkontraste sind nicht
Geschmackssache, sondern eine Testdatei.

**Schnell, auch auf dem Handy im Funkloch.** Seiten werden vorab erzeugt und
liegen fertig aus. Nach einer Änderung im Redaktionssystem wird genau die
betroffene Seite neu gebaut, nicht die ganze Website.

## Gemessen, nicht behauptet

Lighthouse gegen den Produktionsbuild der Startseite:

|         | Leistung | Barrierefreiheit | Best Practices | SEO | LCP   |
| ------- | -------- | ---------------- | -------------- | --- | ----- |
| Desktop | 100      | 100              | 100            | 100 | 0,7 s |
| Mobil   | 94       | 100              | 100            | 100 | 3,2 s |

Der Mobilwert entsteht unter simulierter Drosselung (1,6 Mbit/s, vierfach
verlangsamte CPU). Die Restverzögerung ist die Hausschrift; sie wegzulassen
wäre schneller und schlechter.

Dazu 109 automatische Tests: 59 für Bausteine und Farbkontraste, 50 im echten
Browser für Tastaturbedienung, Formular und die Zusage von oben, dass keine
Verbindung nach draußen geht.

## Was hier liegt

Der Werkzeugkasten und die Kundenprojekte liegen in privaten Repositories —
Preise, Verträge und Kundendaten gehören nicht ins Schaufenster. Öffentlich ist
dieses Profil.

## Ansehen

Die eigene Seite ist zugleich der Arbeitsnachweis:
**[rheingeladen.de](https://rheingeladen.de)**

Sie steht, ist aber noch nicht freigegeben: einzelne Angaben sind Platzhalter,
und für Suchmaschinen ist die Seite bis dahin gesperrt.
