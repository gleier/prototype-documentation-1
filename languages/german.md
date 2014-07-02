---
layout: default
title: Primo Prototyp Dokumentation
---
<div id="content" markdown="1">
##0. Worum geht es in diesem Dokument

![primo play set]({{ site.baseurl }}images/photo/maker-guide.jpg)
Dieses Dokument sammelt und organisiert alle Informationen die notwendigen sind um einen Primo Prototypen zu bauen.
Mehr Informationen zu diesem Projekt findest du im Internet unter [primo.io](http://primo.io).

<h2>
<a href="#" id="translate-title">
    Wie kann dieses Dokument Uebersetzt werden
</a>
</h2>


<div markdown="1" id="translate">

Wenn du dieses Dokument in deine Sprache uebersetzen moechtest hast du mehrere Moeglichkeiten:


1. **sehr einfach, keine Automatisierung** Kopiere diese Seite in deinen Texteditor, uebersetze sie und mail sie an uns [play@primo.io](mailto:play@primo.io)
2. **Durchschnittlich, einwenig Automatisierung** lege einen Zugang bei [GitHub](http://github.com) an und oeffne das [repository dieser Seite](https://github.com/primo-io/prototype-documentation/blob/gh-pages/index.md) und klicke in der oberen Menueleiste auf 'EDIT': 
![photo]({{ site.baseurl }}images/screenshots/edit-1.jpg)
Die Seite zeigt nun einen Texteditor mit dem du den Seitenquelltext modifizieren kannst. Die Seite ist in [markdown](http://daringfireball.net/projects/markdown/syntax) geschrieben und sehr einfach zu verstehen.
![photo]({{ site.baseurl }}images/screenshots/edit-2.jpg)
Du musst den Quelltext nicht mit dem Texteditor der Seite veraendern sondern kannst ihn auch durch Kopieren&Einfuegen einfach in dein Lieblings Textverabreitungsprogramm laden. Uebersetze nur die Textpassagen ohne die Eingeklammerten- und HTML Elemente zu veraendern. Wenn du fertig bist speichere den Text und sende ihn via Email an uns [play@primo.io](mailto:play@primo.io)



3. **Fortgeschritten, Vollautomatisiert** Dies is eine etwas fortgeschrittenere Herangehensweise aber nicht allzu schwierig. Wenn du bisher keine Erfahrungen mit GitHub gemacht hast hast du hier die Chance etwas neues zu lernen :) <br>


Wenn du bereits Erfahrungen mit git gemacht hast musst du nur einen fork des repositorys kopieren. Alle Uebersetzungen befinden sich im "languages" Dateiordner. Um eine Seite zu Uebersetzen kopiere einfach die zu Uebersetzende Sprachdatei (zum Beispiel "english.md") in den selben Ordner und aendere den Dateiname so das er Der zu Uebersetzenden Sprache entspricht (zb. spanish.md). Aednere den Setentitel 'titel' (in den Titel in der zu Uebersetzenden Sprache und 'language' (Die Zielsprache mit Grossgeschriebenem Anfangsbuchstaben. Dannach uebersetze den Rest des Dokuments. Wenn du fertig bist fuehre eine pull anfrage durch um deine Datei dem Repository hinzuszufuegen. Die Datei wird dem Dateimnenue automatisch hinzugefuegt.<br><br>

Erklaerung der oben erwaehnten Schritte:


  1. Lege einen GitHub account an 
  2. Lade die GitHub Programme herunter ([Mac](http://mac.github.com/), [Windows](http://windows.github.com/))
  3. Wenn du die Programme das erste mal benutzt, starte es und gib deine GitHub Anmeldedaten ein.
  4. Gehe zu [this documentation repository](https://github.com/primo-io/prototype-documentation)
  5. Waehle den "Fork" knopf in der oberen rechten Ecke um einen Fork dieses Repositories auf deinen Zugang zu kopieren. 
  6. Oeffne deinen GitHub Zugang oeffne den Fork des Repositories und Klicke "Clone Destop" auf der Rechten navigationsleiste an. Das Git Programm startet nun Automatisch und fraegt nach dem Ort an dem eine Lokalekopie des Repositories angelegt werden soll.
  7. Nachdem du einen Speicherort ausgewaehlt hast klicke "clone"
  8. Oeffne den Zielordner nachdem die Dateien heruntergeladen wurden.
  9. Oeffne den Ordner 'languages'. In diesem befinden sich alle vorhandenen Uebersetzungen. Um eine Seite zu Uebersetzen kopiere einfach die zu Uebersetzende Sprachdatei (zum Beispiel "english.md") in den selben Ordner und aendre den Dateiname so das er der zu Uebersetzenden Sprache entspricht (zb. spanish.md). Dannach uebersetze den Rest des Dokuments.
  10. Oeffne die erstellte Datei und aendre den Seitentitel 'titel' (in den Titel in der Zielsprache) und 'language' (Die Zielsprache mit Grossgeschriebenem Anfangsbuchstaben) ohne die Eingeklammerten- und HTML Elemente zu veraendern.
  11. Nachdem die Uebersetzung fertig und gespeichert ist is es zeit unser Dokument wieder auf GitHub hochzuladen. Oeffne das GitHub Programm und Doppelklicke auf das repository. Klicke auf "Changes" auf der linken navigationsleiste. Nun sollte die Meldung "Uncommited Changes" ausgeben werden.
  12. Gib deinen Aenderungen einen Namen wie zum Beispiel "spanish translation" und Klicke auf "commit" und anschiessend auf "sync".
13. Gehe zu deinem GitHub Profil das sich auf der forked repository Seite befindet. Nun solltest du die neu angelegte Datei im 'languages' Ordner sehen. Darueber sollte ein gruener Knop mit Zwei Pfeilen sein. Klicke diesen um eine pull request anzustossen. (wie am Bild darunter)

  ![photo]({{ site.baseurl }}images/screenshots/pull-1.jpg)

  14. Klicke nun auf "Create Pull Request"

  ![photo]({{ site.baseurl }}images/screenshots/pull-2.jpg)

  15. Schreib eine Nachricht fuer den Pullrequest und schon bist du fertig. Nun muessen wir der Anfrage nur noch Zustimmen.
</div>
<br>

##1. Was ist Primo

![primo play set]({{ site.baseurl }}images/photo/primo.jpg)

Primo ist eine angreifbare Benutzerschnittstelle die Entworfen wurde um Kindern im Alter zwischen 3 und 7 Jahren, die noch nicht Lesen koennen, Prgrammierbare Logik beizubringen. Das Spielziel ist es den kleinen Roboter namens Cubetto zurueck in sein Haus zu fahren. Um dieses Ziel zu erreichen muessen Kinder den kleinen Roboter mithilfe einer beschraenkten Anzahl von Anweisungen(Vorwaerts, Links ,Rechts und Funktion) Programmieren.
Die Aufgabe der ersten 3 Befehle versteht sich Intuitiv. Die Anweisung Funktion ruft eine Subroutine, eine eigene Zeile mit Anweisungen, innerhalb einer einzigen Anweisung auf.

<div class="videoWrapper">
  <iframe src="//player.vimeo.com/video/82620072" frameborder="0" webkitallowfullscreen="true" mozallowfullscreen="true"  allowfullscreen="true">        
    </iframe> 
</div>

##2. Forschung

Kindern Programmieren zu Lehren ist ein weit debatiertes Thema. Wir sind uns einer moderaten Anzahl von Loesungen fuer Kinder ab 8 Jahren bewusst die dies erfuellen sollen. Wie auch immer. Es gibt nicht viele Loesungen die fuer Juengere Kinder gemacht sind und es gibt keine einzige Loesung die ohne Bildschirm oder der Faehigkeit zu Lesen verwendbar ist. Wir sehen eine steigende Anzahl von Applikationen fuer Tablets und andere Computer die das Steuern Physischer Roboter ermoeglichen. Aber keine von diesen sind komplett aus der "pixel domain" losgeloest wie das Primo Play Set.

Holz wurde als das Hauptmaterial ausgewaehlt. Zuallererstmal weil es natuerlich ist, sich warm anfuehlt und weil es gut Klingt. Der zweite Grund ist Kultureller Natur. Beobachtungen in Schweizer Kindergaerten (Das Originaldesign stammt aus der Schweiz) Fuehrten zum Ergebnis das Kinder Holzspielzeug bevorzugen. Holzspielzeuge sind sehr Robust. Dennoch Zeugen Kratzer und Furchen von der Vormaligen Verwendung durch andere Kinder. Sogesehen ist Holz ein Material mit Gedaechtnis. Holz wurde auch deshalb ausgewaehlt weil es im Kontrast zur dahinterliegenden Technik steht. Im Inneren des Primo befindet sich eine beschaltete Platine, wir aber wollten eine "Magische" Erfahrung Vermitteln und versteckten daher die Komplexitaet des Spielzeugs.

<img class="float" src="{{ site.baseurl }}images/photo/logo-turtle.jpg">

Das Konzept hinter Primo ist sehr von der Arbeit von Seymour Papert, einem Mathematiker der in den 60ern gemeinsam mit Marvin Minsky das MIT Artificial Laboratory begruendete, Inspiriert. Interessierten am Thema empfehle ich [Mindstorms](http://www.amazon.co.uk/Mindstorms-Children-Computers-Powerful-Ideas/dp/0465046746/ref=sr_1_1?ie=UTF8&qid=1393675158&sr=8-1&keywords=mindstorms+papert), sein bekanntestes Buch). Er leitete das Team das [LOGO](http://en.wikipedia.org/wiki/Logo_(programming_language)) erfunden hat. Wahrscheinlich die am laengsten existierende Methode Kindern Programmieren beizubringen. Das Ziel von Seymour Papert war nicht nur Programmieren zu lehren, er wollte Kindern dabei helfen ihre eigenen Problemloesungungen zu entdecken. Primo kann als eine sehr starke Vereinfachung von LOGO und dem physischem turtle angesehen werden bei der keinerlei Darstellung von Schrift oder Zahlen verwendet wird.

Der erste Prototyp wurde im SUPSI Lugano von Matteo Loglio (Primo.io Mitgruender und Interaktionsdesigner), waehrend seines [MAInD - Master of Advanced Studies in Interaction Design](http://www.maind.supsi.ch/) gebaut. Matteo's Hintergrund liegt im Produktdesign. Nachdem er um einen Prototypen zu bauen die Grundlagen der Arduinoprogrammierung studierte schaute er sich nach Technischen Loesungen die fuer Anfaenger Nutzbar waren um eine Applikation wie primo zu entwickeln um. Die zwei Hauptthemen waren ein Roboterfahrzeug von Grund auf zu bauen und eine Schnittstelle zu enwickeln die mit einfachen Mitteln die Verschiedenen Anweisungen erkennen kann.

Die erste Aufgabe wurde unter Zuhilfenahme des von David Cuartielles enwickelten [Oh_Oh board](http://david.cuartielles.com/w/Maquila2/Ohoh) geloest. Er ist einer der Arduino Gruender und hielt einen Vortrag im SUPSI. Der Oh_Oh robot ist ein Offenes Projekt. Im Grunde besteht der oh_oh robot aus einem wie ein Auto geformten Arduino. Zur Funkkommunikation wurde ein XBee Funkmodul hinzugefuegt. 

Das zweite Thema war der Entwurf eines Verlaesslichen Weges die Anweisungsbloecke zu erkennen. Eine Loesung war vom [CIID](http://ciid.dk/) Projekt ["Barcode Piano"](http://ciid.dk/education/portfolio/idp11/courses/physical-computing/projects/barcode-piano/) inspiriert.

<div class="videoWrapper">
  <iframe src="//player.vimeo.com/video/19704918" frameborder="0" webkitallowfullscreen="true" mozallowfullscreen="true"  allowfullscreen="true">    
    </iframe>
</div> 

Die Idee ist es Verschiedene Anweisungsbloecke durch die Verwendung unterschiedlicher Widerstaenden zu Identifizieren. Im Prinzip handelt es sich hier um einen simplen Spannungsteiler bei dem die Analogen Eingaenge des Arduino die durch die Widerstaende reduzierte Spannung Messen. Eine sehr Einfache Methode die sich beim Prototypen als sehr effektiv Herausgestellt hat.

Einige Eigenschaften des Entwurfes benoetigten Tests. Der Aktuelle Enwurf ist das Ergebnis mehrerer Durchlaeufe.

Der schlaengelnde 'zik-zak' Pfad der Anweisungssequenz wurde gewaehlt um Schreib- und Lesevorurteile zu vermeiden.
![left to right]({{ site.baseurl }}images/illustrations/left-to-right.jpg)

Die 'D' Form der Anweisungsblockanschluesse wurde so entworfen das sie nur auf eine Art verwendet werden koennen und sich nach dem Pfad und der Fahrrichtung orientieren. Auch andere Formen sind moeglich. Die D Form wurde gewaehlt weil sie ein 'ausgerichteter Kreis ist und als Form an aehnliche Pinwand Entwuerfe erinnert.

![instruction blocks]({{ site.baseurl }}images/photo/instruction-blocks.jpg)

Der Entwurf der Form der Anweisungsbloecke wird noch getestet. Die Formen sind gut Verstaendlich und Kinder Erfassen innerhalb kurzer Zeit deren Bedeutung. Ein Paar Probleme gibt es mit den Links und Rechts Anweisungen. Vermutlich auch weil das Konzept von "Links" und "Rechts" noch sehr neu fuer +4 jaehrige ist. Wir Testen im Moment auch andere Entwuerfe der Anweisungsbloecke um dies weiter zu Verbessern.

<div class="videoWrapper">
  <iframe src="//player.vimeo.com/video/50570097" frameborder="0" webkitallowfullscreen="true" mozallowfullscreen="true"  allowfullscreen="true">
        
    </iframe>
</div>

Am Anfang hatte der Roboter die Form eines Autos. Eine sehr komplizierte Form die viel Zeit bei der Herstellung beansprucht da die einzelnen Teile mit einem Laser cutter geschnitten und Schicht fuer Schicht zusammengeklebt und eine Stunde mit Sandpapier Abgeschmiergelt wurden. Ein anderes Problem war das die Form sehr eher Buben als Maedchen anspricht. Wir wollten eine Diskussion ueber 'Lernspielzeug" das fuer nur Buben gemacht wird vermeiden. Wir wollten neutral bleiben und kein Spielzeug spezielle fuer Maedchen oder Burschen entwickeln also entschieden wir uns fuer eine sehr Neutrale Form. Einen Wuerfel.

Dem kleinen Wuerfel wurde ein Name gegeben zusammen mit einer Personalitaet und einem Laecheln um ihn fuer Kinder noch Attraktiver zu gestalten. Der name des Roboters ist Cubetto (kleiner Wuerfel auf Italienisch). Die Idee hinter Cubetto ist es ein Basismodell zu erschaffen das in Zukunft einfach erweitert werden kann.

![cubetto]({{ site.baseurl }}images/photo/cubetto.jpg)

##3. Erste Schritte

###3.1 Die Grundlagen

Primo besteht aus drei Teilen: Der Benutzerschnittstelle, Cubetto und einem Set von Anweisungsbloecken. Kinder interagieren mit der Benutzerschnittstelle indem sie Anweisungsbloecke in die vorgesehenen Vertiefungen platzieren um eine Sequenz zu erstellen die im Anschluss von Cubetto Ausgefuehrt wird. 

Es gibt vier Typen von Anweisungsbloecken. Das bedeutet das Widerstaende mit 4 verschiedenen Werten benutzt werden koennen. Moeglicherweise solche deren Werte weit voneinander entfernt liegen.

Die Anweisungsbloecke werden in die Vertiefungen der Benutzerschnittstelle gesteckt. Hier wird der Widerstandswert gemessen. Dannach werden die gemessenen Werte Zu einer Ablaufliste verarbeitet und unter der Verwendung von zwei XBee Funkmodulen an Cubetto gesendet. Cubetto fuehrt die Anweisungen dann der Reihe nach aus.

Das Gehirn des Prototypen besteht aus Zwei Arduino Boards, einem UNO (Leonardo oder Duemilanove koennen webenfalls Verwendet werden.) fuer Cubetto und einem Arduino Mega fuer die Benutzerschnittstelle bei der 16 Analoge Eingaenge Vorhanden sein muessen.

###3.2 Elektronik
###Benoetigtes Werkzeug

* Loetkolben
* Loetzinn
* Kabel
* Heissklebepistole
* Leim
* Kupferband (5mm Breit)

###Materialien (Preise in Euro)

Cubetto ~ 88 €

* Arduino UNO (or Leonardo) - 20 € : [Arduino Store](http://store.arduino.cc/index.php?main_page=product_info&cPath=11&products_id=195#.UxC5nfTV_bA)
* Arduino Proto Wireless Shield - 14.90 € : [Arduino Store](http://store.arduino.cc/index.php?main_page=product_info&cPath=37_5&products_id=145#.UxC53vTV_bA)
* SN754410 Motortreiber - 3.90 € : [Arduino Store](http://store.arduino.cc/index.php?main_page=product_info&cPath=6_33&products_id=153#.UxC5-_TV_bB)
* XBee (ob Serie 1 oder 2, macht keinen Unterschied) : 23.90 € - [Arduino Store](http://store.arduino.cc/index.php?main_page=product_info&cPath=37_38&products_id=292#.UxC6cvTV_bA)
* SolarBotics Raeder x 2 : 4.74 € - [Solarbotics Store](https://solarbotics.com/product/gmpw/)
* SolarBotics Getriebemotoren GM3 x 2 : 8.36 € - [Solarbotics Store](https://solarbotics.com/product/gm3/)
* 2 Kugellaufrollen : 5.79 € - [Solarbotics Store](https://solarbotics.com/product/23160/)
* CNY70 x 2 : 1 € - [Mouser](http://uk.mouser.com/ProductDetail/Vishay/CNY70/?qs=%2fha2pyFaduj8YpDhNNtXszq4w32cl%2fAjUjdOwQUvJUM%3d)
* (optional) Batteriehalter : 4 € - [Solarbotics Store](https://solarbotics.com/product/bholdaa_4_cell/)
* (optional) 4 x Akkus

Benutzerschnittstellen Board ~ 88 € (reiner Zufall)

* Arduino Mega 2560 : 39.00 € - [Arduino Store](http://store.arduino.cc/index.php?main_page=product_info&cPath=11&products_id=196#.UxC_gPTV_bA)
* Arduino Proto Wireless Shield : 14.90 - [Arduino Store](http://store.arduino.cc/index.php?main_page=product_info&cPath=37_5&products_id=145#.UxC53vTV_bA)
* XBee (ob Serie 1 oder 2, macht keinen Unterschied) : 23.90 € - [Arduino Store](http://store.arduino.cc/index.php?main_page=product_info&cPath=37_38&products_id=292#.UxC6cvTV_bA)
* 16 5mm Rote LED : 1 € - [Mouser](http://uk.mouser.com/ProductDetail/Lite-On/LTL-4223/?Lite-On/LTL-4223/&qs=sGAEpiMZZMusoohG2hS%252b15J8d1kHl%252bvkJpzS4atZNEA=)
* 16 220 Ω Widerstaende : 0.16 € - [Mouser](http://uk.mouser.com/ProductDetail/Xicon/291-220-RC/?qs=sGAEpiMZZMu61qfTUdNhG%2f1uGo5nxyCVqn6ChOCvUEE%3d)
* 16 10K Ω Widerstaende : 0.16 € - [Mouser](http://uk.mouser.com/ProductDetail/Xicon/291-10K-RC/?qs=sGAEpiMZZMu61qfTUdNhG6xwTrVwTvbz8PPav3aExs8%3d)
* 1 Druckknopf : 1 € 
* 50 Stiftleisten : 1 € 
* 16 Doppelte Stiftleisten : 0.50 € - [Arduino Store](http://store.arduino.cc/index.php?main_page=product_info&cPath=6_32&products_id=294#.UxC_3fTV_bA)
* 50 Buchsenleisten : 1 € - [Arduino Store](http://store.arduino.cc/index.php?main_page=product_info&cPath=6_32&products_id=188#.UxDAAfTV_bA)
* 16 Magnete ø 4 h 3 : 3.5 € - [Supermagnete](http://www.supermagnete.ch/eng/S-04-03-N)

Anweisungsbloecke ~ 4 €

* 4 x 4.7K Ω Widerstaende : 0.04 € - [Mouser](http://uk.mouser.com/ProductDetail/Xicon/291-47K-RC/?qs=sGAEpiMZZMu61qfTUdNhG%2fbdyz6pU6a%252bvHlD5kaZWgo%3d)
* 4 x 100K Ω Widerstaende : 0.04 € - [Mouser](http://uk.mouser.com/ProductDetail/Xicon/291-100K-RC/?qs=sGAEpiMZZMu61qfTUdNhG81NIhcRRUJQxII5Nsctha8%3d)
* 4 x 220 Ω Widerstaende : 0.04 € - [Mouser](http://uk.mouser.com/ProductDetail/Xicon/291-220-RC/?qs=sGAEpiMZZMu61qfTUdNhG%2f1uGo5nxyCVqn6ChOCvUEE%3d)
* 4 x 10K Ω Widerstaende : 0.04 € - [Mouser](http://uk.mouser.com/ProductDetail/Xicon/291-10K-RC/?qs=sGAEpiMZZMu61qfTUdNhG6xwTrVwTvbz8PPav3aExs8%3d)
* 16 Magnete ø 4 h 3 : 3.5 € - [Supermagnete](http://www.supermagnete.ch/eng/S-04-03-N)

###3.3 Stromversorgung

Cubetto und optional auch das Benutzerschnittstellen Board sind Batteriebetrieben. Fuer den Prototypen kannst du entscheiden ob du LiPo Akkus oder einfache AA Batterien verwenden willst. Wir haben beides verwendet. LiPo Akkus sind gut aber benoetigen ein wenig extra Zubehoer. Wenn du gerade anfaengst empfehlen wir AA Batterien. Merk dir aber das diese sehr schnell Leer werden. Am besten ist es wohl NiMh AA Akkus zu verwenden.

###3.4 Prototype Design

Das Produkt ist aus mit Laser geschnittenem Holz gemacht. Vor allem 4mm stark und einer lage mit einer Dicke von 1mm. Du kannst die Einzelteile von Dienstleistern wie Ponoko schneiden lassen oder ein Fablab in deiner Naehe besuchen. Der erste Prototyp wurde im [FabLab Lugano](http://fablab.supsi.ch/) gefertigt. Waehrend die weitere Produktentwicklung im [FabLab Torino](http://fablabtorino.org/) stattfand. Teile des Entwicklerteams befinde n sich immer noch dort.

Cubetto und das Benutzerschnittstellen Board zu bauen ist eine Arbeitsintensive aber sehr einfache Prozedur. Die Huellen sind einfache Schachteln. Die Komplexitaet liegt in der Herstellung der Anweisungsbloecke. Diese bestehen aus zwei 4mm Holzlagen mit Magneten und eingeloeteten Widerstaenden.

##4. Prototype Making

###[Download Source Files](files/primo-prototype-laser.zip)

###4.1 Interface Board

To make the interface board you have to laser cut two files: interface-board-4mm.dxf and interface-board-1mm.dxf: the first one is for 4mm plywood and the second one for 1mm plywood. As you can see from the files, the parts are numbered, to ease the assembly process. The numbers are stored on a different layer, so you can easily remove them before lasering. We recommend adjusting the hole for the push button, based on the size of the button you wish to use or have.

Zuallererst muessen Teil 3 und 4 zusammen geklebt werden. Benutze Schrauben umd die Teile durch die Loecher in den Ecken hindurch ueber Nacht zu fixieren.

Then take the copper tape, cut 32 pieces of 70mm each and put them inside the rectangular holes in the part that you just glued, they should be at least 30mm wide on each side. Once you finished, you can now glue all the remaining top layers of the interface board, this is the correct order:

Then take the copper tape, cut 32 pieces of 70mm each and put them inside the rectangular holes in the part that you just glued, they should be at least 30mm wide on each side. 

![copper connectors]({{ site.baseurl }}images/illustrations/board-1.jpg)
![copper connectors]({{ site.baseurl }}images/illustrations/board-2.jpg)

Once you finished, you can now glue the previously glued parts, 1+2 with 3+4.

![copper connectors]({{ site.baseurl }}images/illustrations/board-esploso.jpg)

Once the glue has dried, put the magnets in the little holes. Turn your top layer upside-down and fill the little holes with the magnets, make sure they are all in the same direction, doesn't matter if north or south. Seal the hole with a drop of hot glue.

Now the electronics. Start by making rails for the 5V and the GND, all along the hole lines like in the picture. The first ever prototype never had copper strips, it had wires (which you can also use), but in this prototype we used copper tape also for the rails. A real 100% time saver. It also makes things easier for creating connections.

![rails]({{ site.baseurl }}images/illustrations/board-3.jpg)

The next step is to wire one of the two connectors of every hole, to the ground rail. If you used copper tape, you can just use a tiny extra bit of it, just enough to touch both ends.

![rails]({{ site.baseurl }}images/illustrations/board-5.jpg)

Now we have to connect the other side of each connector to the 5V rail, but this time, with a 10KΩ resistor in-between. A cool thing of copper tape is that solder melts very well on top of it. This is the technique used:

![10k]({{ site.baseurl }}images/photo/diy-docs-1.jpg)

At the end of this process, you should have something like this:

![10k scheme]({{ site.baseurl }}images/illustrations/board-6.jpg)

Now it's time to put the LEDs; stick one red LED in each one of the 16 holes, then use a drop of hot glue to seal them to the wood. Once the glue is cold, we have to connect them. Just mind that LEDs have a polarity: the long leg is the anode and the short one the cathode. Connect each cathode to the ground rail, using a 220Ω Resistor.

![10k]({{ site.baseurl }}images/photo/diy-docs-6.jpg)

Connect each cathode to the ground rail, using a 220Ω Resistor.

![10k scheme]({{ site.baseurl }}images/illustrations/board-7.jpg)

The long leg of the LED, must be connected to a digital I/O pin on the Arduino Mega, these pins are numbered from 22 to 53. The LEDs must be connected in order, so that it will be much easier to access them later on in the code, in my prototype for example I started from pin number 30 up to 45 (there are 16 LEDs). 
The starting point is not important, as long as they are in the correct sequential order. This means for example that if we start from pin 30, the first LED must be attached to pin 30, the second to pin 31, the third to pin 32 and so on until LED 16 to pin 45. 

The cables are soldered to a rack of double male headers, as the digital pins on the Arduino Mega are laid out in a double line. In this way it's easy to plug and remove the Arduino from the board.

![rack]({{ site.baseurl }}images/photo/diy-docs-4.jpg)

Once all the LEDs are soldered, we have to solder our hand made connectors. These must be wired to the Arduino Mega analog pins, to read the different resistor values. Just like the LEDs, these must be connected in order, starting from A0 for hole 1 to A15 for hole 16. The wire has to start from the same point where we soldered previously the 10K resistor. See the illustration:

![analog input board connections]({{ site.baseurl }}images/illustrations/board-8.jpg)

<div class="cf">
<img class="float cf" src="{{ site.baseurl }}images/illustrations/button.jpg">

<p>
Here I used some single male headers, as the analog pins are all on a single line.
  
</p>

<p>
The last thing to connect is the button: take it and solder two cables to two opposite headers, then slip them trough the button hole, from the top, and push it all the way down, until it stops. Now flip the board, you should have the two wires coming out of the hole. Connect them as in the illustration: one straight to 5V, the other one to GND using a 10k Resistor. Then connect it to an Arduino digital pin from the button-end of the resistor, in this example we used pin number 50.
</p>
</div>


![photo]({{ site.baseurl }}images/photo/diy-docs-5.jpg)

Almost done with the board, now you just have to plug the Wireless Shield on top of the Arduino Mega and stick the headers in place in the board. To recap, 30 to 45 for the LEDs, A0 to A15 for the connectors and 50 for the button. Use the A0 to A5 pins on the Wireless Shield for the first 5 connectors. Don't forget to connect the ground rail to the GND pin and the 5V to the 5V pin.

![rack]({{ site.baseurl }}images/photo/diy-docs-3.jpg)

Now a little bit of fine-tuning: after that part 12 of the board has been painted, you can glue it with part 13 on top of the board.

Same for the red button: after part 14 has been painted, put something soft like cardboard on top of part 2, around the push button, then some hot glue on top of the push button and before the glue dries off, place the red button. See the illustration:

![photo]({{ site.baseurl }}images/illustrations/button-mechanics.jpg)

###INSTRUCTION BLOCKS

This is one instruction block, exploded:

<img class="float cf" src="{{ site.baseurl }}images/illustrations/instruction-esploso.jpg">

To make the Instruction Blocks, the first thing you have to do is laser cut the files, there's one for 4mm thick wood and one for 1mm wood. They are four layers, numbered from 1 to 4 and the drawings provided can be used to make 16 blocks, four of each kind.

Each block has a different resistor. These are the resistors used in the prototype:

FORWARD: 4.7K Ω<br>
LEFT: 100K Ω<br>
RIGHT: 220 Ω<br>
FUNCTION: 10K Ω

To make blocks, first you have to glue part 4 with part 3. 

After the glue has dried, you can start painting. See the illustration below to see what part should be colored:

![image]({{ site.baseurl }}images/illustrations/colors.jpg)

Now you have to cut two pieces of copper tape, 40mm long. Slip them in the holes of the two blocks that you just glued, making a ring around it using the upper and lower fissure, the ring must be quite tight.

![photo]({{ site.baseurl }}images/illustrations/instruction-block-guide.jpg)

After that, you have to put the magnet in the hole. While doing this, BE SURE THAT IT IS CORRECTELY ORIENTED, so that the block 'sticks' into the hole. If you put it the other way, it's going to be repelled by the other magnet, a funny outcome but not what we want to achieve.

Fix the magnet with a drop of hot glue and before the glue gets cold, put the right resistor on top, with the 'legs' laying on the copper tape. After that, the resistor must be soldered on the two pieces. After soldering, cut the extra leg length and glue part 2 on top of the resistor.

Finish your block by gluing the last layer, part number 1, on the top, then repeat the entire process for every single block :)

###CUBETTO

Electronics:

The prototype for Cubetto can be built using an Arduino Uno or Leonardo, with a Proto Wireless Shield on top. The reason for the Proto Shield is because it has a small prototyping area, that is wide enough to put the motor driver, the connectors for the optical encoders, motors and power. 

Cubetto has to spin 90 degrees left and right. A very inaccurate way is to use timing event, like "spin right for one second" and you can expect more or less the same result. "More or less" because it depends a lot from different factors, such as the floor, the battery power and so on. The way I solved this problem, is by detecting the amount of rotation from the wheel using two CNY70 optical encoders in combination with a sticker. The round sticker goes in the inner wheel and it's something like this:

![photo]({{ site.baseurl }}images/photo/diy-docs-14.jpg)

The sticker is split into black and white slices, this is because the CNY70 is able to detect the variation between a white slice and a black one. Basically inside it has an infrared LED that is always on and a phototransistor that is reading the amount of infrared light. When a black material is facing the component, almost no light is relfected, as the black color tends to absorb it. On the contrary, if the material is white, it reflects all the light, so the value read from the sensor it's very high. The difference between readings is used to count the rotation steps.

![photo]({{ site.baseurl }}images/illustrations/cny70-physycs.jpg)

The prototyping area of the Wireless Proto Shield is where the motor driver and other connectors for the other parts are soldered. For these, simply use male headers as connector and female headers on the other part.


![photo]({{ site.baseurl }}images/illustrations/wireless-shield-connections.jpg)

For these I used simple male headers as connector and female headers on the other part.

![photo]({{ site.baseurl }}images/photo/diy-docs-12.jpg)

![photo]({{ site.baseurl }}images/illustrations/wireless-shield-connections-1.jpg)

The SN754410 motor driver has 16 pins that must be connected following this scheme:

![photo]({{ site.baseurl }}images/illustrations/motor-driver.jpg)

The CNY70 scheme:

<img style="width:50%" src="{{ site.baseurl }}images/illustrations/cny70-wiring.jpg">

Design:

Start by lasering cubetto.dxf; All Cubetto parts are cut from 4mm plywood, follow these visual instructions to build the base:

![photo]({{ site.baseurl }}images/illustrations/cubetto-guide.jpg)

Don't mount the motors for now, first you have to mount the ball casters.

![photo]({{ site.baseurl }}images/illustrations/ball-caster.jpg)

![photo]({{ site.baseurl }}images/photo/diy-docs-9.jpg)

Now the CNY70. Solder the two opposite headers, that must be connected to 5V, together with a wire; then solder three wires to the remaining headers of the CNY70. At the end of these wires solder a row of three female headers. They will later be connected on to the headers of the proto shield.

The two cny70 must be placed on the edge of the bottom layer, with the LED and the photoransistot horizontally aligned. To fix them you can use some hot glue (or other types of glue). 

See the picture to understand the location.

![photo]({{ site.baseurl }}images/photo/diy-docs-11.jpg)

Just like for the CNY70, solder two wires to the little flaps that come out of each motor. You can twist the two wires to make them more resistent, then at the end, solder a row of two female header, just like in the illustration.

Now print the inner drawing with the black and white slices, glue them on a piece of cardboard (or laser cut wood, that's up to you), cut the perimeter and make a hole in the middle, as they will be inserted between the motor and the wheel. The white and black slices must point towards the inner side of Cubetto and the distance between the print and the CNY70 must be between 1 and 3 millimeters for the CNY70 to work properly.

![photo]({{ site.baseurl }}images/photo/diy-docs-10.jpg)

Now you can put the wheels on the motors, if you used the Solarbotics wheels, you can fasten them with the screw provided, don't make it too tight. 

Glue three out of the four 'walls' of Cubetto, parts 5, 7 and 8. We are going to leave the back removable, just in case we want to modify something. 

Take the battery holder and solder the black and red cable to other 2 female connectors. The headers on the shield will go to VIN and ground. A switch that breaks the red wire is heavily suggested.

![photo]({{ site.baseurl }}images/photo/diy-docs-13.jpg)

Now you can place the Arduino + Proto shield on top of the motors, plug all the headers on the shield and you have finished making Cubetto.
</div>

##Arduino

###[Download Arduino Files](https://github.com/primo-io/arduino-sketches/raw/master/primo-prototype-arduino.zip)

Instructions in the sketch comments.
