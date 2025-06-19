# 🐞Bugs & Support

## Bei Problemen

Bitte erstellt ein Ticket bei unserem [IT-Support](https://julis.de/it-support/). Bitte beachtet, dass die Antwortzeiten oft einige Tage lang sind, weil wir diese Leistungen großteils ehrenamtlich zur Verfügung stellen.

## Bekannte Probleme & Lösungen

Hier führen wir alle bekannten Fehler, oft gestellte Fragen und Probleme sowie deren Lösungen auf.

=== Meine Lizenzen wurden nicht aktiviert

Bitte stelle zunächst sicher, dass die Lizenzen wirklich nicht aktiviert wurden. Folgende Lizenzen sollten aktiviert sein, das Ganze sollte so aussehen:

**Elementor Pro:**

![](/static/graphicsregio/2-lizenz1.jpeg)

![](/static/graphicsregio/2-lizenz2.jpeg)

**Crocoblock:**

![](/static/graphicsregio/2-lizenz3.jpeg)

![](/static/graphicsregio/2-lizenz4.jpeg)

**Wenn dies nicht der Fall ist, wende dich bitte an den IT-Support!**

===

=== Ich bekomme den Wartungsmodus nicht ausgestellt

Den Wartungsmodus könnt ihr im WordPress-Dashboard in der Kopfzeile ausschalten:

![](/static/graphicsregio/2-wartungsmodus1.jpeg)

===

=== Ich finde meine Seite nicht bei Google oder anderen Suchmaschinen

Bei Auslieferung des Regiosystems erhaltet ihr eine neue Instanz, die hinter einer Stagingdomain zur weiteren Einrichtung liegt. Erst nach einem Signal von euch, schalten wir diese hinter eure Domain live. Diese Liveschaltung unsererseits bedeutet nicht, dass wir den Wartungsmodus abschalten. Das müsst ihr selber erledigen. Gleichzeitig deaktivieren wir nicht das Indexierungsverbot für Suchmaschinen. Das bedeutet, dass ihr ohne Änderung nicht auf Google und Co. gelistet werdet. 

### Schritt 1: WordPress-Einstellungen prüfen
Wir bitten euch, die Einstellung nachzuschauen unter Einstellungen => Lesen => „Sichtbarkeit für Suchmaschinen“ und dort ggf. den Haken zu entfernen.

![](/static/graphicsregio/2-lesen.jpeg)

 Es kann durchaus 24-48h dauern bis sich eure Suchergebnisse verbessern.

### Schritt 2: Google Search Console
Bei weiterführenden Sichtbarkeitsproblemen lohnt es sich, auch einen Blick in u.a. die Google Search Console zu werfen: https://search.google.com/search-console

===


=== Termine oder Events werden nicht auf der Startseite angezeigt. ODER Der Operator "Greater or Equal" in einer Query verschwindet oder lässt sich nicht speichern.

### Problem:

![](/static/graphicsregio/2-termine1.jpeg)

### Lösung:
1. Navigiert zu Jet Engine > Query Builder

![](/static/graphicsregio/2-termine2.jpeg)

2. Dort erstellt ihr eine neue Query 

![](/static/graphicsregio/2-termine3.jpeg)

3. Die Einstellungen sind analog zu der Logik bei anderen Queries

![](/static/graphicsregio/2-termine4.jpeg)

![](/static/graphicsregio/2-termine5.jpeg)

![](/static/graphicsregio/2-termine6.jpeg)

![](/static/graphicsregio/2-termine7.jpeg)

**Bitte beachtet das Format des current_date.**

4. Meta Query auf der Start- und Archivseite für Termine einbinden.

![](/static/graphicsregio/2-termine8.jpeg)

Hinweis: Bitte beachtet, dass Termine OHNE Datum immer angezeigt werden. 

===


=== Das JuLi-Logo wird im Firefox-Browser nicht angezeigt.

**Problem:**

Firefox hat einige Probleme mit SVG-Dateien.

Beispielhafter Aufruf über Chrome:

![](/static/graphicsregio/2-logo1.jpeg)

Beispielhafter Aufruf über Firefox:

![](/static/graphicsregio/2-logo2.jpeg)

**Lösung:**

Klickt dazu im WordPress Dashboard auf: Design-Customizer.

Wählt dann die Website-Informationen aus:

![](/static/graphicsregio/2-logo3.jpeg)

Klickt nun auf "Logo wechseln".

![](/static/graphicsregio/2-logo4.jpeg)

Sucht in der Medienübersicht einfach nach "Logo" und wählt die Datei "230508_Logo_YaufM_RGB.png" aus. Wählt dann im Zuschnitt das gesamte Logo aus.

Jetzt noch speichern und veröffentlichen und der Fehler ist behoben.

===


=== Fehlerhafter Link im mobilen Menü

**Problem:**

Bei einigen Regiosystemseiten gelingt die automatische Aktualisierung der Links beim Umzug auf die richtige URL nicht. Dies führt dazu, dass beim Klicken auf "Mitglied werden" z.B. auf regio.julis.de/mitglied-werden weitergeleitet wird, diese Seite aber nicht existiert.

**Lösung:**

Navigiert im Backend zu dem Templates und wählt dort das Template Mobile Menü | Submenü aus. Bearbeitet dieses mit Elementor.

![](/static/graphicsregio/2-menu1.jpeg)

Hier könnt ihr jetzt einfach den fehlerhaften Link ersetzen durch https://julis.de/mitglied-werden/ .

![](/static/graphicsregio/2-menu2.jpeg)

===

=== Abschnitte sind nicht mehr farbig und lassen sich nicht farbig machen.

Dies lässt sich in der Regel mit einer erneuten Generierung der CSS-Daten lösen.

![](/static/graphicsregio/css-new.png)

Andernfalls meldet euch beim IT-Support.

===

=== Bei der Personenvorschau wird das im Vorschaubild ungewöhnlich stark gezoomed.

Dieses Problem tritt meistens beim Design 2 auf, und betrifft entweder einen _Shortcode_ oder die Einzelpersonenansicht.

**Shortcode:**
1. Loggt euch bei WordPress ein.
2. Navigiert zu _Templates_ und wählt dort das Template _Shortcode Person Design 2_ aus, um diese _mit Elementor zu bearbeiten_.
3. Hier könnt ihr entsprechende Anpassungen am Beitragsbild machen, siehe Bild. Hier muss man ausprobieren, was am besten passt. Meistens ist die vorgegebene Einstellung sogar richtig und die Methode - ändern, aktualisieren, zurückändern, erneut aktualisieren - löst in der Regel schon das Problem.


**Einzelpersonenansicht**

1. Loggt euch bei WordPress ein.
2. Navigiert zu einer Seite, wo das Problem auftritt.
3. Auf der Seite klickt auf: _mit Elementor bearbeiten_ -> _Single Post_ (Das ist die Template vorlage für die automatisch generierten personenseiten).
4. Hier könnt ihr entsprechende Anpassungen am Beitragsbild machen, siehe Bild. Hier muss man ausprobieren, was am besten passt. Meistens ist die vorgegebene Einstellung sogar richtig und die Methode - ändern, aktualisieren, zurückändern, erneut aktualisieren - löst in der Regel schon das Problem.

![](/static/graphicsregio/design-personen.png)

===