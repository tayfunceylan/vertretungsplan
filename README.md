# Vertretungsplan
<img src="pictures/logo.jpg" alt="logo" width="150">

## Einleitung
Viele Programmierprojekte sind aus Frust entstanden, so auch dieses Projekt.
Sobald sich etwas auf unserem Vertretungplan ändert, wollte ich eine 
Benachrichtigung bekommen. Alle relevanten Informationen, wie zum Beispiel "Fach X 
hat Raumverlegung in Raum Y", sollen in den Benachrichtigungen enthalten sein.

## Einrichtung

Das Einrichten des Bots verlangt kein zusätliches Wissen. Es ist simpel gestaltet.
Der Bot fragt zuerst in welche Stufe der Schüler geht. Anschließend werden die Fächer
abgefragt, die vom Schüler besucht werden. Daraufhin werden die Kurse abgefragt.
Abschließend wird das Setup mit einer Frage nach einem username und dem password
des Vertretungsplans beendet.

<img src="pictures/einrichtung.gif" alt="Einrichtungsvideo" width="300">

## Berichte

Sobald der Vertretungsplan morgens von der Schule hochgeladen wird, werden an alle
registrierten Nutzer des Bots personalisierte Berichte des Vertretungsplans geschickt.
Das Format ist (Stunde | Fach | Raum | statt Fach | Bemerkungen).
Hier ist ein Beispiel-Bericht:

<img src="pictures/example_message.jpg" width="300" alt="Beispiel für ein Bericht">

## Befehle

### /heute, /morgen, /tag

Mit dem Befehl /heute wird der Stundenplan von heute abgerufen. Zusätzlich dazu
wird auch angeben, in welchem Raum unterrichtet wird.

<img src="pictures/heute.jpg" alt="Klausurplan Beispiel" width="300">

### /klausurplan

Hiermit lässt sich der Klausurplan abrufen. Dieser Befehl sucht für den Nutzer
den zur Stufe zugehörigen Klausurplan als PDF direkt von der Hompage unserer Schule.

<img src="pictures/klausurplan.jpg" alt="Klausurplan Beispiel" width="300">

### /kalender

Dieser Befehl holt sich den aktuellen Kalender von der Homepage der Schule und
zeigt die Einträge hier an. Mit den Pfeiltasten kann durch die Wochen gegangen
werden.

<img src="pictures/kalender.jpeg" alt="Kalender Beispiel" width="300">

### /profile

Mit diesem Befehl kann man überprüfen, ob man die richtigen Kurse aboniert hat.

<img src="pictures/profile_oberstufe.jpg" alt="Profil" width="300">

### /friend

Der Bot bietet auch ein Freundesystem. Mit einem / gefolt von dem Nutzernamen des
Freundes lässt sich eine Freundesanfrage verschicken. Nimmt dieser an, so lässt
mit dem gleichen Befehl der Stundenplan und Vertretungsplan des Freundes ansehen.

### /friends

Mit diesem Befehl lassen sich alle Freunde anzeigen, die durch das Freundesystem
hinzugefügt wurde.

### /help

Dieser Befehl listet alle verfügbaren Befehle und eine kurze Erklärung

## Sonstiges

### Artikel

Sobald ein Artikel auf unserer Homepage hochgeladen wurde, haben alle Nutzer eine
Nachricht erhalten mit Foto, Überschrift, die ersten Sätze des Artikels und einem
Link zum Artikel.

<img src="pictures/artikel.jpg" alt="Profil" width="300">

## Statistiken

### Nutzerentwicklung

Dieses Tool, ursprünglich für den eigenen Gebrauch, hat sich schnell
in der Schule rumgesprochen. Das führte dazu, dass es gegen Ende meiner Schulzeit
ungefähr 150 Nutzer dieses Projekts gab. Die schnellen Anstiege Mitte September und
Ende November sind jeweils durch eine Nachricht in einen Klassenchat entstanden.

<p>
    <img src="pictures/entwicklung_april_07.png" alt="Entwickling der Nutzeranzahl">
    <em>Stand: 07.04.2019</em>
</p>

### Klassenverteilung

Der Verteilung der Stufen sieht folgendermaßen aus. In der Q2 sind natürlich die
Benutzer, da ich selbst aus der Q2 bin. Interessant ist, dass es auch vereinzelnt
Nutzer in der Unterstufe gibt. Muss durch Mundpropaganda passiert sein.

<p>
    <img src="pictures/stufenverteilung.png" alt="Verteilung der Stufen">
    <em>Stand: 13.02.2019</em>
</p>