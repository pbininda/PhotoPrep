# PhotoPrep

Vorbereitungen für einen Safari-Trip mit Kamera

# Anforderungen

* Photos sollen mit hoher Qualität aufgenommen werden.
* Photos sollen nicht verloren gehen.
* Wenig Gepäck soll nötig sein.
* Randbedingung: Die meiste Zeit steht keine vernünftige Internetverbindung zur Verfügung.

# Der Plan

* Photos werden mit einer Spiegelreflexkamera geschossen.
* Die Photos werden auf der Kamera auf SD-Karte gespeichert.
* Um bei Defekt einer SD-Karte den Schaden zu minimieren werden mehrere kleinere SD-Karten statt einer großen mitgenommen.
* SD-Karten werden bei Bedarf getauscht.
* Bei gelegenheit (Abends) werden die geschossenen Photos auf eine portable Festplatte gesichert.
* Zur Sicherung wird folgendes Setup verwendet:
  * Festplatte und Kamera werden an einen USB-Hub angeschlossen.
  * Android-Smartphone wird mit USB-OTG-Adapter als Host an den USB-Hub angeschlossen.
  * Über einen Android-Dateimanager werden die Photos von der Kamera auf die Festplatte kopiert.
  * Die Festplatte wird unter Android deaktiviert / ausgeworfen bevor das Setup getrennt wird.
* Alternatives Setup zur Sicherung:
  * Die SD-Karte wird aus der Kamera entnommen und in ein (ausgeschaltetes) Android-Smartphone eingesetzt.
  * Die Festplatte wird mit USB-OTG-Adapter an das Android-Smartphone angeschlossen.
  * Über einen Android-Dateimanager werden die Photos von der SD-Karte auf die Festplatte kopiert.
  * Die Festplatte wird unter Android deaktiviert / ausgeworfen bevor das Setup getrennt wird.
  * Das Android-Smartphone wird wieder heruntergefahren und die SD-Karte wird wieder entnommen.
* Es werden mehrere Akkus für die Kamera mitgenommen so dass immer ein geladener Akku zur verfügung steht.

# Hardware / Anschaffungen

## Smartphone: Samsung Galaxy S10e

https://smile.amazon.de/gp/product/B07SC8MD9H

<img width="300px" src="https://images-na.ssl-images-amazon.com/images/I/61gTbPNPKNL._SX679_.jpg">

## Kamera: Nikon D3500

https://smile.amazon.de/gp/product/B07GZP6JPG

<img  width="400px" src="https://images-na.ssl-images-amazon.com/images/I/71uWjflifoL._SX679_.jpg">

## SD-Karten: 4 * SanDisk Extreme microSDXC 128GB + SD Adapter

https://smile.amazon.de/gp/product/B07FCMKK5X

<img  width="200px" src="https://images-na.ssl-images-amazon.com/images/I/81TTUPZWacL._SX569_.jpg">

## Festplatte: Seagate STEA1000400 Expansion Portable 1 TB

https://smile.amazon.de/gp/product/B00TKFEEAS

<img  width="300px" src="https://images-na.ssl-images-amazon.com/images/I/91VmFqLG7EL._SX569_.jpg">

## USB-Hub: atolla USB Hub mit Netzteil, USB 3.0

https://smile.amazon.de/gp/product/B07P6MPXJ7

<img  width="300px" src="https://images-na.ssl-images-amazon.com/images/I/61kqt5TMWSL._SX679_.jpg">

## USB-Hub: Anker Ultra Slim Extra Leicht 4 Port USB 3.0 Hub

<img  width="300px" src="https://images-na.ssl-images-amazon.com/images/I/31meaTVecFL.jpg">

## USB-OTG-Adapter: BENFEI USB C Adapter auf USB 3.0

https://smile.amazon.de/gp/product/B07DNQ9FD9

<img  width="200px" src="https://images-na.ssl-images-amazon.com/images/I/61bCMDJ93oL._SX679_.jpg">

## Ersatz-Akkus: Newmowa Ersatz Akku EN-EL14 (2er Pack), USB Ladegerät

https://smile.amazon.de/gp/product/B00V5ORSYQ

<img  width="300px" src="https://images-na.ssl-images-amazon.com/images/I/71d%2BqIHB6fL._SX679_.jpg">

# TODO

## Strom

In Südafrika haben sie 230V 50Hz, so weit gut.

Die Steckdosen sind die Typen D, M, N. Unsere Stecker könnten in Typ N passen. Details müssen noch geklärt werden. Gggf. Reiseadapter besorgen.

Siehe: https://www.welt-steckdosen.de/suedafrika/#targetText=In%20S%C3%BCdafrika%20betr%C3%A4gt%20die%20Netzspannung,der%20in%20Deutschland%20identisch%20ist.

## Plan Testen

Zu klären:

* Kann man vom Smartphone aus via USB vernünftig auf die Kamera zugreifen so dass man die Bilder kopieren kann?
* Funktioniert das zuverlässig mit einem nicht aktiven USB-Hub? (Anker) Oder muss der aktive USB-Hub verwendet werden?
* Wie lange dauert das kopieren der Photos und wie viel Akku saugt das vom Smartphone?

# Testergebnisse

* Zugriff auf die Kamera funktioniert via MTP. Die "Downloads App" öffnet sich nach Anschluss der Kamera und man kann mit dieser App von der Kamera auf die Festplatte kopieren.
* Bisher habe ich keinen Kopiermodus gefunden, der bereits kopierte Bilder überspringt...
* Mit einem (alten) passiven Hub funktioniert es, sofern man den Hub via USB-3 Stecker (mit extra Stromversorgungs-Pins) via USB-OTG-Adapter anschließt.
* Das Kopieren dauert relativ lange. Für einen Tag Photos schätze ich ca. 1 Stunde Kopierzeit.
* Der Akku des Smartphone wird nicht besonders belastet. Es sollte bei einigermassen vollem Akku gut funktionieren.

# Tutorial / Walkthrough

## Geräte Anschließen

### Teile im Überblick

<img width="800" src="pictures/a-01-parts.jpg">

### Festplatte anschließen

<img height="330" src="pictures/a-02-hdunplugged.jpg"> <img height="330" src="pictures/a-03-hdplugged.jpg">

### Kamera anschließen

<img height="230" src="pictures/a-04-camera-off.jpg"> <img height="230" src="pictures/a-05-camera-unplugged.jpg">

<img height="210" src="pictures/a-06-camera-plugged.jpg"> <img height="210" src="pictures/a-07-camera-on.jpg">

### Smartphone anschließen

<img height="235" src="pictures/a-08-otg-unplugged.jpg"> <img height="235" src="pictures/a-09-otg-plugged.jpg">

<img height="260" src="pictures/a-10-phone-unlocked.jpg"> <img height="260" src="pictures/a-11-phone-connected.jpg">

### Fertig

<img width="800" src="pictures/a-12-ready-to-copy.jpg">

## Kopieren

<img width="250" src="screenshots/a-01-launcher.jpg"> <img width="250" src="screenshots/a-02-choose-download.jpg"> <img width="250" src="screenshots/a-03-download-sidebar.jpg"> 

<img width="250" src="screenshots/a-04-to-dcim.jpg"> <img width="250" src="screenshots/a-05-in-dcim.jpg"> <img width="250" src="screenshots/a-06-select-100dc3500.jpg"> 

<img width="250" src="screenshots/a-07-menu.jpg"> <img width="250" src="screenshots/a-08-sidemenu-to-usb.jpg"> <img width="250" src="screenshots/a-09-contents-hd.jpg"> 

<img width="250" src="screenshots/a-10-new-folder.jpg"> <img width="250" src="screenshots/a-11-name-new-folder.jpg"> <img width="250" src="screenshots/a-12-start-copy.jpg"> 

<img width="250" src="screenshots/a-13-wait.jpg"> <img width="250" src="screenshots/a-14-eject.jpg"> <img width="250" src="screenshots/a-15-finished.jpg"> 

### Hier noch mal als Animation

<img width="400" src="screenshots/animated-process.gif">