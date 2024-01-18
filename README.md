# pics_viewer
Short script to present pictures on a website

Bilderbetrachter f&uuml;r Webseiten - **Foto - Viewer**
<br>
Version 1.6
<br>
Autor: Hans-Peter Dorn
[Webseite:](https://hapede.de/ "Meine Homepage")
<br>
**Funktionsweise:**
<br>
Den Download entpacken und auf den Webserver kopieren.
Einbinden von *viewer.php* in die entsprechende Seite, an der Stelle, an der die Bilder angezeigt werden sollen.
Beispiel:
<br>
'&lt?php
include ('viewer.php')
?>'
<br>
Kopieren der Bilder in das Verzeichnis *pics*.
<br>
**Einstellungen**
<br>
In der Datei *settings.json* k&ouml;nnen einige Einstellungen ge&auml;ndert werden:<br>
Das Bildverzeichnis *dirs* kann ge&auml;ndert werden. Default: **pics**
Die anzuzeigenden Bildtypen *include_files* kann ge&auml;ndert werden. Default: **.jpg**
Der Titel der Anzeige *title* kann ge&auml;ndert werden. Default: **Titel**
Die Größe der Bilddarstellung wird in der Datei VIEWER.CSS eingestellt: 
    <br>grid-template-columns: repeat(auto-fit, minmax(20em, 2fr));</br>
    Der Wert 20 beeinflusst die Bildgröße.
Der Vergrößerungsfaktor beim Überfahren mit dem Mauszeiger wird an zwei Stellen in der Datei VIEWER.CSS eingestellt. Siehe Zeile: /*Vergrößerungsfaktor*/

**History**

Version 1.6: MouseOverunterstützung bei kompatiblen Touchgeräten
Version 1.5: Verbesserungen Mouseover, Maps Icon
Version 1.4: mehrere Bild-Typen zulässig
Version 1.3: GPS Link zu Google-MAPS 
Version 1.2: Verbesserung der Ansicht
Version 1.1: Vergrößerung der Bilder bei Mausover

**Hinweis**

TIF-Dateien werden von Browsern nicht angezeigt

**TO DO**
//TODO Verzeichnisse ignorieren
