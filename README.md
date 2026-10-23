# Zusammenfassung meiner CAD-Erfahrung

## Vorwort

Bei der Erstellung dieser Projekte wurde hauptsächlich Autodesk Fusion 360 verwendet.
Für das Design von Leiterplatten verwendete ich Autodesk Eagle, welches mittlerweile in Fusion 360 integriert wurde.  
Weitere relevante Software, mit der diese Projekte erstellt wurden, stellen FreeCAD und KiCad dar.
Diese wurden dabei jedoch eher zu Lernzwecken verwendet und sobald es ernster wurde mit Fusion 360 und Eagle ersetzt, um von dem ausgereifteren Workflow zu profitieren.  
Wichtig zu erwähnen ist, dass ich in meinen bisherigen Arbeitsverhältnissen und Universitätskursen weitere Software verwendete:

 -  Autodesk Inventor, um das Design unseres autonomen Lagerroboters "Herbie" zu unterstützen
 - Altium Designer, wenn auch nur in begrenztem Umfang, vor allem um Kollegen bei der Fehlersuche zu unterstützen
 - SolidWorks für das Design eines Roboters für den Kurs "Mechatronische Systeme und Produkte"
 - CorelDRAW zur Erstellung von Vektordateien, um Spanplatten mittels Lasercutter zurechtzuschneiden
 - SketchUp, welches kurzzeitig zur Erstellung von beispielhaften Anlagenaufbauten für Kunden verwendet wurde

 Da die mit diesen Software-Tools erstellten Projekte Teil meiner Werkstudententätigkeiten oder Gruppenarbeiten waren, kann ich sie hier leider nicht vorführen.  
 Jedoch habe ich mich ausführlich mit mehreren Freizeitprojekten befasst, die ich Ihnen in diesem Dokument vorstelle.

## 3D Modelle

Die meisten 3D Modelle, die zu den Projekten gehören, waren nicht gut für den Export geeignet, da sie aus vielen Einzelteilen bestehen.  
Im entsprechenden Ordner finden Sie jedoch zwei 3D Modelle, welche ich sowohl in Form von STL-, als auch STEP-Dateien exportiert habe.  
Da die Modelle viele interessante Details enthalten, hielt ich es für angebracht, sie zur genaueren Betrachtung in dieser Form abzulegen.

[[Modellübersicht]](<https://github.com/YoshuaMFrey/YoshuaMFrey.github.io/tree/main/3D%20Modelle>)  

Rahmen der Drohne aus dem unten genannten Projekt  
[[STL]](<3D Modelle/DroneFrame.stl>)  
[[STEP]](<3D Modelle/DroneFrame.step>)

Solarlaterne aus dem unten beschriebenen Projekt  
[[STL]](<3D Modelle/SolarLaterne.stl>)  
[[STEP]](<3D Modelle/SolarLaterne.step>)

## Größere Projekte
Größere Projekte sind in den einzelnen PDF Dateien zu finden.  
Hier eine kurze Übersicht:

### Low-Cost-Drohne
[Drohnenprojekt.pdf](Drohnenprojekt.pdf)
enthält die Zusammenfassung eines langfristigen Projektes, mit dem ich mich immer wieder befasste. 
Dies ist vor allem ein Übungsprojekt, mit dem ich verschiedene Designansätze ausprobiert habe. 
Sowohl CAD als auch ECAD spielten hier eine Rolle. 
Ersteres vor allem beim Design des eigentlichen Drohnenkörpers. 
Dieser durchlief dutzende Iterationen und ist vor allem im frühen Studium für mich eine Übung im Design von Leichtbau-Bauteilen gewesen.

### Elektromagnetisches Schachbrett
[Schachbrettprojekt.pdf](Schachbrettprojekt.pdf)
enthält ein aktuelleres Projekt, was hauptsächlich in ECAD stattfand. 
Es ist ein laufender Versuch, ein "Harry Potter"-inspiriertes Schachbrett zu bauen, welches ohne Motoren die Schachfiguren bewegt. 
Derzeit ist vor allem die korrekte Ansteuerung der Elektromagnete die ausstehende Herausforderung.  

## Kleinere Projekte

### Zykloidalgetriebe

![Zykloidalgetriebe](/Bilder/CycloidalGear.gif)

Ein Zykloidalgetriebe ist eine besonders platzsparende Form des Getriebes, welche enorm hohe Übersetzungen erreichen kann und dabei sehr wenig Spiel hat.
Ein inneres "Laufrad" wird auf einer exzentrischen Welle angebracht und an den Rand des Gehäuses gedrückt.
Das Gehäuse wiederum enthält eine andere Anzahl von Zähnen als das Laufrad.
Dadurch muss sich das innere Rad drehen, um sich der Form des Gehäuses anzupassen. 
Die Übersetzung berechnet sich aus der Anzahl der Zähne des inneren Rads und der des Gehäuses.  
In dem Design, welches ich hier vorstelle hat das innere Rad 7 Zähne und das Gehäuse 8.
Die durch die Ungleichheit entstehende Übersetzung beträgt 1 zu 7.
Damit vollendet das Laufrad eine Umdrehung für alle 7 Umdrehungen der Exszenterwelle in der Mitte.  
Um den Mechanismus besser zu verstehen erstellte ich dieses 3D-Modell und die Animation.

---

### Gyroskop

![Gyroskop](/Bilder/Gyroscope.gif)

Ein recht einfaches Gyroskop.  
Dieses war ursprünglich als Teil einer Testplattform für das Drohnenprojekt geplant.  
Die Lagerungen der Achsen sind so gestaltet, dass standardisierte Kugellager hineingedrückt werden können.
Das halboffene Design hält diese mittels Formschluss fest und sorgt dafür, dass das Gyroskop sehr einfach mit dem 3D-Drucker ausgedruckt werden kann.  
Vor allem ist, wie bei den meisten Gyroskopen, die Animation sehr schön anzusehen.

---

### Plattform zur Erkennung von Identifikationsnummern

![Identnummer-Erkennung](/Bilder/CodeScanningSetup.png)

Das wahrscheinlich professionellste Beispiel in diesem Portfolio, da dieses tatsächlich für eine Projektvorstellung für Kunden gedacht war.
Aus dem damit verbundenen Projekt ist jedoch leider keine Partnerschaft zustande gekommen, was mir aber ermöglicht, es Ihnen hier vorzustellen.  
Grundsätzlich sehr einfach aufgebaut, ging es darum die Identifikationsnummern von Bauteilen in einer laufenden Produktionsstätte zu erfassen, ohne den bestehenden Prozess zu stören.
Der wirklich interessante Teil des Projektes wäre die KI-gestützte Erfassung in der Software hinter der Kamera gewesen.  
Immerhin gab mir dies einen Anlass, mittels dem Material-System von Fusion 360 ein hochwertiges Rendering der Konstruktion zu erstellen, auch wenn die (maßstabsgetreuen) Aluminiumprofile im Bild vielleicht etwas mehr glänzen als in der ursprünglichen Werkshalle.

---

### Solarlaterne

![Solarlaterne](/Bilder/SolarLaterne.jpeg "Solarlaterne")

Als Geschenk für eine Nachbarin wollte ich mich an einem einfachen Projekt versuchen, und habe mich am Ende wohl etwas verkünstelt.  
Prinzipiell ist der Aufbau recht simpel.
Die Laterne enthielt mehrere LEDs und einen handgelöteten Ladeschaltkreis, der mithilfe einer Solarzelle im Sonnenlicht die Batterie auflädt.
Sobald die Spannung, die von der Solarzelle geliefert wurde, nicht mehr reichte um die Batterie zu laden, wurden die LEDs angeschaltet.
Trotz des einfachen Aufbaus erleuchtete der Schaltkreis mehrere Jahre lang den Garten.  

Beim Design wurden fünf verschiedene 3D-gedruckte Bauteile verwendet. Die "Fenster" der Laterne wurden von innen mit einer Plastikfolie beklebt, welche die Witterung abhielt und das Licht der LEDs sanfter erscheinen lies.

Wie oben erwähnt finden Sie das zugehörige 3D-Modell im entsprechenden Ordner.

---

## Ende

Herzlichen Dank, dass Sie sich die Zeit genommen haben, sich mein Portfolio anzuschauen!  
Falls Sie dies noch nicht getan haben, möchte ich Ihnen nahelegen, sich auch die Projekte in den PDF-Dateien in dieser Mappe anzuschauen.  
Sollten beim Lesen Fragen aufgekommen sein, würde ich mich sehr freuen, diese mit Ihnen zu besprechen.  

Viele Grüße und einen angenehmen Tag

### Yoshua Frey
