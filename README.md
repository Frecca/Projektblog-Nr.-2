# Projektblog 

Projektblog von Frederik Peters und Rebecca Scholz

## Inhaltsverzeichnis

[08.12.2020](#einf1)

[10.12.2020](#einf2)

[11.12.2020](#einf3)

[07.01.2021](#einf4)

[11.01.2021](#einf5)

[15.01.2021](#einf6)

[19.01.2021](#einf7)

[23.01.2021](#einf8)

[31.01.2021](#einf9)

[01.02.2021](#einf10)

[06.02.2021](#einf11)

[13.02.2021](#einf12)


## Beginn des Projektblogs

### <a name="einf1"></a> 08.12.2020
In dieser Stunde werden wir uns damit beschäftigen, Ideen für unser neues Informatikprojekt zu sammeln.

### <a name="einf2"></a> 10.12.2020
Auch heute informieren wir uns weiter über mögliche Programme, mit denen wir unser nächstes Projekt programmieren können und legen dabei den Fokus auf Greenfoot. 

### <a name="einf3"></a> 11.12.2020
In dieser Stunde beschäftigen wir uns weiter mit Greenfoot und entdecken die zahlreichen Funktionen des Programms.

### <a name="einf4"></a> 07.01.2021
Wir haben uns heute Gedanken darüber gemacht, wie wir unser nächstes Projekt gestalten wollen. Wir haben uns bereits für Greenfoot entschienden und wollen ein Spiel programmieren, bei dem es auf Geschicklichkeit ankommt. Der Spieler soll also die Spielfigur steuern und somit das Ziel des Spiels erfüllen. 

### <a name="einf5"></a> 11.01.2021
Mit Hilfe der Links von Herrn Buhl haben wir uns erste Szenarien auf Greenfoot angesehen und ausprobiert. Hierzu zählten die Little Crab und die Cat.

### <a name="einf6"></a> 15.01.2021
Heute haben wir die Greenfoot Bücher bekommen und konnten uns somit die ersten Schritte für die Programmierung mit Greenfoot aneignen. Zunächst haben wir uns einen Überblick über das Buch verschafft und dann einzelne Kapitel durchgelesen.

### <a name="einf7"></a> 19.01.2021
Wir haben uns weiter mit dem Buch und den Funktionen von Greenfoot beschäftigt. Des Weiteren haben wir uns im Internet verschiedene Projekte, die mit Greenfoot programmiert wurden, angesehen, um Ideen für unser eigenes Projekt zu finden.

### <a name="einf8"></a> 23.01.2021
Heute planen wir unser Projekt. Dafür haben wir zunächst ein eigenes Szenario auf Greenfoot erstellt und verschiedene Funktionen ausprobiert. In unserem Szenario hat ein Flusspferd einen Apfel gegessen. Der Quellcode dafür sah wie folgt aus:

![eigenes Szneario](https://github.com/Frecca/Projektblog-Nr.-2/blob/main/Hippo.png)

Danach haben wir uns auf ein Projekt festegelgt, welches wir programmieren möchten. Es handelt sich um ein Spiel für zwei Spieler, die gegeneinander antreten müssen. Das Spiel ist inspiriert an "Teletennis". Wir haben uns einen Überblick darüber verschafft, was wir alles programmieren müssen und wie wir unser Spiel gestalten wollen.

### <a name="einf9"></a> 31.01.2021

Wir haben uns heute Gedanken darüber gemacht, wie wir die nächsten Schritte unseres Projektes angehen. Wir wollen zunächst auf Greenfoot die World erstellen, also den Hintergrund unseres Spieles erstellen. Wenn das Spielfeld fertiggestellt ist, können wir mit den Spielfiguren und deren Programmierung fortfahren. Morgen wollen wir die World programmieren.

### <a name="einf10"></a> 01.02.2021

Heute beginnen wir damit, unser Spiel zu programmieren. Wir haben zunächst eine Skizze angefertigt, die die wesentlichen Funktionen und den Ablauf des Spiels beinhaltet. 

![Skizze unseres Projektes](https://raw.githubusercontent.com/Frecca/Projektblog-Nr.-2/main/Skizze.jpg)

Unser Spielfeld ist die World. Wir haben uns hier für einen schwarzen Hintergrund enschieden, der an das Weltall erinnert. Unsere Actor bestehen aus dem Ball und den Playern, Player_1 und Player_2. 
Die Player haben die Möglichkeit, den Ball mittels Steuerung nach oben und unten abzuwehren und somit zurück zum Gegenspieler zu schießen. Der Ball soll, sobald er die obere oder untere Wand der Welt berührt, abprallen. Dabei beträgt die Größe des Einfallswinkels die Größe des Ausfallswinkels. Berührt der Ball eine Wand hinter einem der Player, so ist dies ein Punkt für den entsprechenden Spieler, da das Ziel des Spiels ist, den Ball nicht auf die Wand auftreffen zu lassen. 
Die Skizze unseres Projektes sieht folgendermaßen aus:

In Greenfoot haben wir die World und die Actor erstellt. 

![World und Actor](https://raw.githubusercontent.com/Frecca/Projektblog-Nr.-2/main/World%20and%20Actors.png)

Unsere einzelnen Actor sehen bislang so aus:

Player 1:

![Bild Player 1](https://raw.githubusercontent.com/Frecca/Projektblog-Nr.-2/main/Player_1.png)

Player 2:

![Bild Player 2](https://raw.githubusercontent.com/Frecca/Projektblog-Nr.-2/main/Player_2.png)

Ball:

![Bild Ball](https://raw.githubusercontent.com/Frecca/Projektblog-Nr.-2/main/Ball.png)

Wir müssen in den nächsten Stunden noch die Größen der einzelnen Actor anpassen, da diese noch nicht stimmen. Aktuell sieht das Spielfeld mit allen Actorn so aus:

![aktuelles Bild des Spielfeldes](https://raw.githubusercontent.com/Frecca/Projektblog-Nr.-2/main/Spielfeld_01.02.2021.png)

Außerdem haben wir mit der Programmierung der Steuerung des ersten Spielers Player_1 begonnen. Wir haben die Bewegungsrichtung festegelegt. Diese erfolgt senkrecht nach oben und unten über die Pfeiltasten. Bei Player_2 wird mit "W" und "S" gesteuert. Zudem haben wir beim Player_1 die Größe angepasst. Der Editor des ersten Spielers sieht nach heutigem Stand folgendermaßen aus:

![Programmierung Player_1](https://raw.githubusercontent.com/Frecca/Projektblog-Nr.-2/main/Player%201%20descr.png)

### <a name="einf11"></a> 06.02.2021

Beim letzten Mal hatten wir nach dem Speichern das Problem, dass der Player_1 sich nicht mehr bewegen lassen hat und immer eine Fehlermeldung kam. Auf Grund dessen konnte kein Spieler mehr gesteuert werden. Wir haben heute den Fehler gefunden: Die Länge des Player_1 war so weit dezimiert, dass er nicht mehr existiert hat. Wir haben die Größeneinstellung geändert. 
Nach dieser Fehlerbehebung haben wir die Größen von Player_1 und Player_2 angepasst und den Ball auf eine passende Größe minimiert. 
Des Weiteren haben wir eine neue Actorklasse eingefügt - die Goals, also den Bereich, der die Tore der Spieler darstellt. Diese sind farblich passend zum Spieler markiert, sodass die Zuordnung leicht erfolgen kann. In dem Code unserer Welt haben wir die Player_1, Player_2, den Ball, und die beiden Goals eingefügt, sodass diese schon von Beginn an in der Welt, also auf dem Spielfeld erscheinen. 

Das Spielfeld sieht im Ruhezustand folgendermaßen aus:

![aktuelles Spielfeld](https://github.com/Frecca/Projektblog-Nr.-2/blob/main/Screen-d.png)

Die dazugehörige Programmierung für die Startposition in unserer Welt lautet:

![Programmierung der Startposition](https://github.com/Frecca/Projektblog-Nr.-2/blob/main/Screen-e.png)

Momentan haben wir folgende Klassen in unserer Welt:

![Klassen in unserer Welt](https://github.com/Frecca/Projektblog-Nr.-2/blob/main/Screen-f.png)

Um unsere Programmierungen übersichtlicher zu gestalten, haben wir damit begonnen, Kommentare einzufügen und unsere Programmierungen bündig einzurücken.

![Kommentare und Einrücken](https://github.com/Frecca/Projektblog-Nr.-2/blob/main/Screen-c.png)

Außerdem haben wir uns einen Überblick darüber verschafft, was wir noch alles programmieren müssen, um unser Spiel funktionsfähig zu machen. Darunter zählen die Programmierung der Spieler, die den Ball abwehren respektive schießen sollen sowie die Programmierung der Goals. Sobald der Ball ein Goal berührt, soll dieser zurück an den Spielanfang gesetzt werden. Am größten wird der Programmierumfang des Balls. Bei diesem müssen wir sowohl die Ballgeschwindigkeit und eine zufällige Bewegung programmieren als auch die Interaktionen mit den Spielern, Goals und übrigen Wänden. Hierunter fallen der Abprallwinkel und die Zurücksetzung an die Startposition.

### <a name="einf12"></a> 13.02.2021

Wir haben damit angefangen, unseren Ball zu überarbeiten und haben ein neues Bild eingefüt. Das Spielfeld sieht durch diese Änderung wie folgt aus:

![Änderung des Balls]()
