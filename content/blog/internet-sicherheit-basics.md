---
title: "Internetsicherheit Basics"
date: '2024-01-05'
author: Anna Breyer
image: images/blog/internet-security.png
tags: ["Internetsicherheit Basics","passwortmanager", "passwortstrategien"]
---

Heute möchte ich Dir mehr zum Thema Internetsicherheit erzählen.

Wir kennen fast alle jemanden dessen Account gehackt worden ist. Und dann denken wir "ich müsste mal was tun, damit
mir das nicht passiert". Doch oft wissen wir nicht, wo wir anfangen sollen.

Ich stelle Dir ein paar Strategien und Möglichkeiten vor, um Deine Internetkonten sicherer zu machen. Welche davon zu Dir
passen, bleibt Dir selbst überlassen.

### Sicherheitsrisiko E-Mail

Je öfters Du Deine E-Mail-Adresse nutzt, desto höher ist das Risiko, dass sie in einem Datenleck veröffentlicht wird.
Und ist sie erst mal "da draußen", dann wird auch irgendwann jemand auf die Idee kommen zu versuchen sich damit bei 
Facebook, Netflix oder anderem einzuloggen.  

#### Wie kann ich prüfen, ob meine E-Mail-Adresse in einem Datenleck zu finden ist?

Dafür gibt es eine Webseite, die von mehreren Sicherheitsexperten gebaut und instandgehalten wird.

https://haveibeenpwned.com/

Dort kannst Du Deine E-Mail-Adresse überprüfen und Dich anmelden, um informiert zu werden, sobald Deine E-Mail-Adresse in einem Datenleck auftaucht.

#### Wie kannst Du das Risiko verringern?

Mehrere E-Mail-Adressen sind eine Lösung. Es gibt genug Möglichkeiten eine kostenlose E-Mail-Adresse im Internet zu erstellen.
Die kannst Du dann an Deine primäre E-Mail-Adresse weiterleiten lassen.  
Oder noch besser Du nutzt ein „Hide My E-Mail“ Feature. Diese Funktion erlaubt es Dir eine temporäre oder anonyme E-Mail-Adresse zu generieren, die anstelle Deiner echten E-Mail-Adresse verwendet werden kann. Diese anonyme E-Mail-Adresse ist mit Deinem eigentlichen E-Mail-Konto verknüpft und E-Mails die an diese Adresse gesendet werden, werden an Deine eigentliche E-Mail-Adresse weitergeleitet.

Das gibt es bei Apple iCloud (kostenpflichtig, ab 0,99 EUR/Monat), aber auch bei dem auf Sicherheit spezialisierten Browser {{< newtabref href="https://duckduckgo.com/" title="DuckDuckGoGo" >}} (kostenfrei),
{{< newtabref href="https://simplelogin.io/vs-apple-hide-my-email/" title="Simple Login" >}} (2,50 EUR/Monat) und {{< newtabref href="https://addy.io/" title="AnonAddy" >}} (kostenlos bis 3 EUR/Monat).
Auch der Passwortmanager {{< newtabref href="https://1password.com/de" title="1Passwort" >}} bietet diese Funktion an. Mehr zu Passwortmanagern im nächsten Abschnitt.

### Passwörter

Wir kennen es alle, das Post-it mit dem Computer Passwort, oder dasselbe Passwort (Name des Haustiers) in allen Accounts und dass seit 10 Jahren.
Wir wissen auch alle, dass das schlecht ist, und dass wir jedes Passwort nur 1x nutzen sollten und auch noch regelmäßig ändern sollten. Doch wer betreibt solch einen Aufwand?

Die Lösung ist einfach, der Passwortmanager.
Der schlägt Dir Passwörter vor, merkt sich jedes für Dich und teilt Dir mit, ob Du es schon einmal verwendet hast oder ob es in einem Leck gefunden wurde (und somit in den Hacker-Passwortsammlungen vertreten ist).

Hast Du einen Passwortmanager, musst Du Dir nur noch 1 Passwort merken, dass für Deinen Manager. Alle anderen merkt er sich für Dich.


#### Welcher Passwortmanager?

Es gibt jede Menge Testberichte zu dem Thema, im Endeffekt hängt viel davon ab was Dir bei einem Passwortmanager am wichtigsten ist.
-	Muss alles auf Deutsch sein oder ist auch Englisch ok?
-	Möchtest Du den Ort wählen, an dem Deine Passwörter gespeichert werden?
-	Gibt es eine Kostenfrage?
-	Soll die Oberfläche intuitiv sein?
-	Gibt es einen Bedarf an geteilten Passwörtern innerhalb der Familie?
-	Soll er auf verschiedenen Betriebssystemen laufen (damit fällt z.B. der von Apple raus)

Mit den folgenden Passwortmanagern kannst du wenig falsch machen.
https://1password.com/de
https://www.dashlane.com/de
https://bitwarden.com/
http://www.safe-in-cloud.com/en/index.html
https://nordpass.com/password-managers/


#### Wie erstelle ich ein komplexes Passwort, dass ich mir merken kann?

Ein Passwort wie *Wn3<27-L1xp?* kann sich kein Mensch so wirklich merken. Was Du Dir aber merken kannst, ist ein Sprichwort, ein Liedertext oder ein Zitat. Und dann nimm die Anfangsbuchstaben jedes Wortes, achte auf Groß- und Kleinschreibung und Zeichensetzung.

Aus dem Lied „Alle meine Entchen“ würde dann:

AmEsadS,sadS.KidW,SidH.

Alle meine Entchen schwimmen auf dem See, schwimmen auf dem See.
Köpfchen in das Wasser, Schwänzchen in die Höh.


Einfacher zu merken, oder?

#### Und warum speichere ich nicht einfach meine Passwörter in meinem Browser?

Das ist keine gute Idee, denn da sind sie nicht sicher geschützt. Mehr dazu kannst du hier lesen.  
https://www.kaspersky.de/blog/how-to-store-passwords-securely/30389/

#### Und warum reduziere ich nicht meine Passwörter in dem ich "Einloggen mit" verwende?

Mit dieser Option sparst Du Zeit, und sie ist praktisch. Aber Du machst Dich dadurch auch angreifbarer und
teilst mehr Daten mit diesen Diensten. Mehr dazu kannst du hier lesen.  
https://www.onlinesicherheit.gv.at/Services/News/Social-Login.html


### Sicherheitsstufen

Es gibt verschieden Stufen von Sicherheit, die ein Konto braucht, und das hängt damit zusammen welche persönlichen Datendarin gespeichert sind.

#### Höchste Sicherheitsstufe

Diese betrifft Konten mit Zahlungsinformationen, wie z.B. PayPal. Sie sollten auf jeden Fall durch eine 2FA geschützt werden.
2FA steht für "2-Faktor-Authentifizierung" und bedeutet, dass Du außer Deinem Passwort noch eine andere Möglichkeit hast Dich beim Einloggen zu identifizieren. Oft ist das eine SMS an Deine Telefonnummer.
Allerdings bietet auch das ein Sicherheitsrisiko, falls Hacker Zugang zu Deiner Telefonnummer bekommen haben.
Eine gute Alternative sind Apps auf Deinem Handy. Entweder eine Authentication App (wie z.B. Authy) oder die App des Anbieters, wie z.B. bei Paypal, wo Du in der App bestätigen kannst, dass Du es bist die sich gerade versucht einzuloggen. Einige Passwortmanager bieten jetzt auch 2FA-Codes an.
Zudem sollte Dein Passwort besonders komplex sein und die E-Mail-Adresse möglichst wenig genutzt sein.

#### Mittlere Sicherheitsstufe

Hier gibt es keine Bankdaten, aber dafür persönliche Daten wie Telefonnummer und Geburtstag. Das ist oft der Fall bei sozialen Netzwerken.
Auch hier empfiehlt sich eine 2FA, denn ein gehacktes Social Media Konto kann schnell viel Schaden anrichten.

#### Untere Sicherheitsstufe

Zur untersten der drei Stufen gehören Onlineshops, bei denen Du nur Deine Adresse hinterlegt hast. Hier reicht es, wenn Du Dein Konto nur mit einem Passwort schützt.

Das sind allgemeine Sicherheitsstufen, je nachdem wie Du im Internet agierst, können Deine Sicherheitsbedürfnisse anders sein.

#### Meine persönliches Sicherheitssetup sieht so aus:

-	Eine extra E-Mail-Adresse für Onlineshops und Newsletter
-	Eine extra E-Mail-Adresse (komische mit Buchstaben und Zahlen) für sensible Daten, staatliche Konten und Streamingdienste
-	Ich nutze den Apple Passwortmanager
-	2FA ist überall aktiviert wo es möglich ist
-	Authy oder die 2FA-Option von Apples Passwortmanager, statt Handynummer, wenn immer möglich
-	Ich nutze „Hide My Email“ von Apple
-	Die E-Mail-Adresse meines Apple Account wird nirgendwo anders verwendet, und kann somit nicht geleakt werden. Das Passwort wird auch nirgendwo anders verwendet und ich ändere es alle 6 Monate.

Bisher gab es 2 Hackingversuche auf meine Konten, die ich mitbekommen habe. Einmal vor über 10 Jahren bei Facebook und in jüngerer Vergangenheit bei Netflix. In beiden Fällen hatte ich noch die geleakte E-Mail-Adresse aber glücklicherweise ein anderes Passwort.
Inzwischen hat keines meiner wichtigen Konten mehr eine geleakte E-Mail-Adresse.

![Sicherheit](/images/blog/feeling-safe.png)