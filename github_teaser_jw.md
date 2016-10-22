						
Zwei Beispiele, was Github leistet
==================================

.

.

Beispiel 1: Die Satzung des Vereins soll überarbeitet werden
-------------------------------------------------------------

Die Vorlage zur Diskussion und Abstimmung muss möglichst
klar sein, was geändert wird.
Mit der Zeit sammeln sich Änderungen an. Wie organisiert man 

 - Transparenz, Reichweite
 - Diskussion im Vorfeld?
 - Fehlerfreiheit?
 - Versionierungen?

.

.

Github ist eine geeignete Plattform. Eigentlich zur
Entwicklung von Software, aber auch andere Texte können hier
verwaltet werden.  Insbesondere die Versionierung stand am
Anfang im Vordergrund.

.

.

.

Zugriffsrechte
--------------
"Ordnung muss sein!"

 - Als Vereinsvorstand kann ich direkt Text-Änderungen machen.
 - Jeder darf lesen, und 
 - Jeder darf Änderungsvorschläge schicken.

http://github.com/fablabnbg/Dokumente
 - Satzung.md


.

.


Sichtbarkeit, Fehlerfreiheit
----------------------------
 - Änderungswünsche als 'Issue' ("Problem") erstellen.
   https://github.com/fablabnbg/Dokumente/issues?q=is%3Aissue+is%3Aclosed
 - Konkrete Textänderung.
 - Diskussionsargumente und Entscheidungen bleiben nachvollziehbar.
 - Prinzip der vielen Augen.

Eine Änderung:
https://github.com/fablabnbg/Dokumente/issues/15

.

.

.



Beispiel 2: Typische Softwareentwicklung im Linux-Umfeld
--------------------------------------------------------

Cura ist ein Programm zum Steuern von 3D-Druckern.
Ich habe mit einem speziellen Kunststoff wieder ein Problem damit, 
dass der Druck gleich zu Beginn des Drucks sich von der Platte löst.
Wenn ich von Hand während der ersten Schicht mehr Material
zuführe, verschwindet das Problem.


.

.

.

Mein Problem ist nicht neu und wurde bereits 2014 gelöst.
Schauen wir uns das an, wie:

Ich befrage meine Suchmaschine:
 "cura platform adhesion over extrusion feature"


Und bekomme Antwort:
 https://github.com/daid/LegacyCura/issues/769

.

.

.

Source Code
-----------

Welche Dateiformate hatten wir hier? 

Beispiel 1:
Bei Vereinssatzungen denkt man normalerweise an *.PDF
Dateien.  

Die Satzung wie ich sie gezeigt hatte war im Textformat
"Markdown". 

 https://github.com/fablabnbg/Dokumente/blob/master/Makefile

.

.

.

Beispiel 2:
Bei Programmen denkt der Windows-Mensch normalerweise an *.EXE Dateien.

Cura ist ebenfalls komplett Open Source. 
Cura ist in Python und C++ geschrieben. Hier wird ein
Compiler verwendet, um ausführbare Programme (Beispielsweise *.EXE 
für Windows)

.

.


Es werden hier aus einer Quelle mehrere Programm-Varianten
gebaut. Für Linux, für Windows und für Mac. Alle nötigen
Schritte dazu sind auch offengelegt, Ich kann damit
Änderungsvorschläge auch selbst erarbeiten, und
ausprobieren.  Das ist bei typischer kommerzieller
Windows-Software überhaupt nicht möglich.

.

.

.

Vorteile durch Open Source

 - Fehler können offen diskutiert werden, 
 - Lösungen werden gemeinsam erarbeitet.
 - Durch die Nachvollziehbarkeit, kann man später die
   Diskussion und lösung leicht finden.

Also

- Auf Facebook zeigen Leute, was sie zum Frühstück hatten.
- Auf Github zeigen Leute, was sie Neues schaffen.

.

.

.

Danke!
======

