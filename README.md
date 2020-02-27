# Karteikarten Analysis
Karteikarten für den Kurs "Fortgeschrittene Analysis für Physiker" an der TU Dresden (2017 -2018).

Die Karteikarten sind für das Programm Anki gedacht (https://apps.ankiweb.net/).
Um anzufangen braucht ihr Anki und Latex (mit den benutzten Paketen, sehe den Header in den tex Dateien ) installiert haben.
Dann braucht ihr nur noch die `.apkg`Datei im Anki zu öffnen. Alternativ könnt ihr auch mit den pdf Dateien aus dem Repository lernen. 

Auf Nachfrage kann ich auch den Deck mit den vor-generierten Karten hochladen, dass sollte, solange ihr die Karten nicht bearbeitet, auch ohne Latex funktionieren.
Die Datei wird nur eventuell ziemlich groß, da alle Karteikarten dann als Bilder gespeichert sind. 

## Wenn ihr die Karteikarten editieren, erweitern, korigieren möchtet:
Die tex Dateien lassen sich in Anki mit dem Plugin( https://tentativeconvert.github.io/LaTeX-Note-Importer-for-Anki/) importieren. 
Der Plugin erlaubt es die Karteikarten in einer Tex Datei zu editieren, statt es direkt im Anki zu machen. Das ist viel effektiver. 
Die Karteikarten lassen sich auch updaten, ohne dass euer Fortschritt bei Anki verloren geht.
Das geht, weil jede Anki "Notiz" einen einzigartigen UUID im ihren ersten Feld hat. Falls ihr neue Notizen erstellt, lassen sich die UUIDs mit dem python Script automatisch genieren.
