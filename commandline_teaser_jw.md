Die Kommandozeile
=================

Eines der mächtigsten Werkzeuge in
Linux ist die "shell". 
Windows-Menschen erwarten da nichts, deswegen möchte ich zeigen "was geht."

.

.

.

Wer hat Angst vor der Kommandozeile?
------------------------------------

 - Man sieht nichts.
 - Man könnte etwas kaputt machen.
 - alles in englisch. 
 - unverständliche Meldungen.
 - Ich mag keine schwarzen Fenster, 
   das sieht ja aus wie MS-DOS

.

.

.

Warum mag ich keine graphischen Oberflächen?
--------------------------------------------

"Die Maus macht alles leichter" - "Auch Fehler..."

 - Wenn ich mich verklicke, passieren Dinge.
 - Maus-schubsen ist oft präzisionsarbeit.

 - Keine klare Rückmeldung
   Warte ich, oder wartet der Computer?

 - Überladene Oberfläche.
   Ich find das Menü nicht mehr...

.

.

.

Alles das sind Vorurteile. Die Realität:
Es sind zwei "Sprachen", die beide ihre Berechtigung haben.

Das Vokabular einer graphischen Oberfläche (oder auch einer 
Webseite) besteht aus:
 - Mausbewegungen, 
 - Gesten, draufklicken, 
 - Knöpfen, 
 - Scrollbalken, 
 - Fenstern und Rähmchen, 
 - Text eingeben...

Das Vokabular einer Kommandozeile ist reduziert. Es besteht aus Text:
 - Worte, 
 - Kommandos, 
 - Parameter,
 - Umleitungen, Strukturen.


Handbücher und Hilfestellungen
------------------------------

Wir haben kein Fragezeichen zum anklicken, kein Mouse-over.

 - Viele Kommandos haben eingebaute Hilfe, die man mit der Option '-h' oder
   '--help' abrufen kann.
 - viele Kommandos haben ausfühliche Dokumentation im System, die man mit einem
   eigenen Kommando abrufen kann.
   'man diff'

Das Eva-Prinzip
---------------

"Einfache Dinge sind gut"

Auf der Kommandozeile findet man immer wieder:

 - Eingabe
 - Verarbeitung
 - Ausgabe

Solche klare Strukturen sind in graphischen Oberflächen oder Webseiten
oft auch vorhanden, aber werden immer mehr versteckt.
Beispielsweise: Wie beende ich die Eingabe, um die Verarbeitung anzustossen?

Save oder OK Knopf. Modern ist "Abspeichern durch daneben-klicken."

.

.

.


Zwei Beispiele
--------------

.

.

pdfcompare 
 - diff patch

.

.

.

vim
 Paste URL in text.
 !!xargs curl 
 --> full text.


.

.

Reality-Check
-------------

Wir Software-Entwickler sind sparsame Leute, wenn es darum geht etwas zum Funktionieren zu bringen.
Wir lassen alles weg, was nicht unbedingt nötig ist. Das hilft, um schnell zum Ziel zu kommen.

Das hilft leider dem Endbenutzer oft wenig, wenn er nicht erklärt bekommt, 
