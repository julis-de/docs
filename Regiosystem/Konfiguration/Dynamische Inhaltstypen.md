# Dynamische Inhaltstypen

### Beiträge

[_Zur Videoanleitung_](https://jliberale.sharepoint.com/:v:/s/Bundesvorstand/Efvk5f4QmV5IjJcVXxxwedsBJ40y0pNlApwUnCkUzART0Q?e=Dodk9C)

Beiträge sind die Inhaltsseiten, die nachher auf der Startseite unter Aktuelles und Neuigkeiten (in der Regel auf der Startseite zu finden) auftauchen. Wichtig ist, dass man Beiträge in verschiedenen Kategorien einsortieren kann. WordPress hat standardmäßig Kategorien und Schlagwörter, wir nutzen lediglich die Kategorien.

Zum Erstellen eines Beitrags klickt in der Menüleiste auf _Aktuelles à Erstellen_. Dann solltet ihr die folgenden Felder ausfüllen:

-   Titel (im Editor)
    
-   Inhalt (im Editor) – dieser kann im Editor flexibel gestaltet werden. Das ist für Pressemitteilungen oder Beschlüsse aber selten notwendig.
    
-   URL [a.k.a _Slug_] (rechtes Menü -> Beitrag), kann nach der ersten Veröffentlichung bearbeitet werden
    
-   Veröffentlichungsdatum (rechtes Menü -> Beitrag), hierüber können auch Beiträge geplant oder rückdatiert werden.
    
-   Kategorie (rechtes Menü -> Beitrag -> Kategorie), kann eigenständig erstellt werden.
    
-   Beitragsbild (rechtes Menü -> Beitrag -> Beitragsbild)
    

Kategorien lassen sich vom Dashboard aus in der linken Menüleiste _Aktuelles -> Kategorien_ (hierarchisch) verwalten.

### Personen

[_Zur Videoanleitung_](https://jliberale.sharepoint.com/:v:/s/Bundesvorstand/EasrEp-Y4SFCrYa0cvvST9oB1YMdDzCL1iRIzXF-WwzHow?e=gFC9De)

Personen können vom Dashboard aus in der linken Menüleiste unter _Personen_ verwaltet werden. Personen lassen sich auch über QuickEdits gut bearbeiten und können in Kategorien (wie bei Beiträgen) verwaltet werden.

Zum Erstellen einer Person klickt auf _Neue Person_. Die relevanten Felder sind vor allem:

-   Name – Das Format ist euch überlassen, weshalb ihr dieses konsistent nutzen solltet. Es gibt keine eigenen Felder für Vor- und Nachname.
    
-   Funktion/Titel – Amt bei den Jungen Liberalen
    
-   Beruf
    
-   Aufgaben
    
-   E-Mail-Adresse
    
-   Social-Media-Kanäle
    
-   Kachelfarbe – hier habt ihr (Soft) Magenta, Cyan und Gelb zur Auswahl
    

Im rechten Menü könnt ihr

-   eine Kategorie setzen
    
-   und das Profilbild setzen.
    

Klickt im Anschluss auf Veröffentlichen.

**Einbinden von Personen auf Inhaltsseiten**

Um Personen bei Beiträgen einzubinden, öffnet das entsprechende Personenprofil im WordPress-Backend. In der URL findet ihr dann eine ID, die ihr zum Einbinden benötigt. Z. B.:

https://julis.de/wp-admin/post.php?post=12345&action=edit -> Hier ist die ID: 12345

Um ein Personenprofil in einem Beitrag einzubinden könnt ihr einfach

[person id=“12345“] oder [person id=“12345“ design=“2“]

im WordPress-Editor einbinden.

In Elementor funktioniert das genauso über das Objekt _Shortcode_. Oder ihr nutzt das sog. _Listing Grid_. Beim Listing Grid könnt ihr in den Einstellungen _Posts Query_, entweder _Tax Query_ oder _Posts & Author Parameters_ nutzen.

**Tax Query**: Hiermit könnt ihr ganze Personenkategorien auflisten. Dazu gebt ihr einfach unter _Terms_ die ID der Personenkategorie (erneut in der URL zu finden) ein.

**Posts & Author Parameters**: Hiermit könnt ihr eine oder mehrere Personen auflisten. Dazu gebt ihr einfach unter _Terms_ die IDs (erneut in der URL zu finden) der entsprechenden Personen getrennt durch ein Komma ein. Über die Ergänzung eines _Order&Offset-_Elements unter _Posts Query_ könnt ihr diese sortieren.

### Termine

[_Zur Videoanleitung_](https://jliberale.sharepoint.com/:v:/s/Bundesvorstand/Eb603DH2Cx1Pju-e5DoliN8BWpo7g8iySNK9KDk3eHiDfA?e=C3owqe)

Termine findet ihr vom Dashboard aus in der linken Menüleiste unter _Termine_. Termine lassen sich sowohl über QuickEdit, über den WordPress-Editor als auch für die detaillierte Eventseite über Elementor bearbeiten. Die wichtigsten und funktionalsten Einstellungen könnt ihr unten im Menü im WordPress-Editor verwalten. Dazu gehören insbesondere:

-   Ob es ein mehrtägiges Event ist
    
-   Startdatum (und Enddatum)
    
-   Veranstaltungsort
    
-   Anmeldelink (z.B. Anmeldeformular)
    
-   Teilnahmelink (z.B. Zoom- oder Discord-Link)
    

Lediglich ein Titel und ein Startdatum sind notwendige Daten.

Wichtig: Bei Terminen gibt es zwei Arten von Daten. Es gibt das Datum der Veröffentlichung (ab diesem ist der Termin für Nutzer sichtbar) und das Veranstaltungsdatum. Unter QuickEdit ist ersteres das _Datum_ und zweiteres das _Startdatum_.

Gestaltung der Eventseite: Die Eventseite könnt ihr gestalten über die Bearbeitung im WordPress-Editor oder über Elementor.

**Tipp**: Solltet ihr häufig Termine derselben Art haben, bei denen bspw. wesentliche Teile der Beschreibung gleichbleiben, so könnt ihr alte Termine einfach duplizieren.

### Downloads

[Zur Videoanleitung](https://jliberale.sharepoint.com/:v:/s/Bundesvorstand/ES9vy_pZYk5FuAPnfJYLB5MBEJqaoIKNFXOPXV-xHHAoUg?e=KsNxEC)

Navigiert vom Dashboard aus zum Punkt Downloads. Hier habt ihr dann die Möglichkeit, alle Download-Dateien zu sehen, die ihr anbietet. Die Downloads werden im Frontend unter der Domain (z.B. unter [_www.julis.de/download_](http://www.julis.de/download))  angezeigt.

Downloads dem Menü hinzufügen: Die Seite Downloads ist nicht standardmäßig im Menü verlinkt. Das heißt ihr könnt euch selbst entscheiden, ob ihr diese braucht oder nicht. Zum Hinzufügen verweisen wir einmal auf das Kapitel _Menü_.

Downloads erstellen: Downloads könnt ihr im Wesentlichen wie andere Inhalte erstellen. Klickt dazu einfach auf _Neuer Download_ und füllt die entsprechenden Felder aus. Das Feld _Link zur Bestellung_ dient dazu, einen Anbieter oder ein konkretes Produkt per URL anzugeben, unter der das downloadbare Design bestellbar wäre. Das Bild zum Download lässt sich wie sonst auch im Menü an der rechten Seite setzen.

Auch bei Downloads könnt ihr wieder mit Kategorien und Taxonomien arbeiten. Die Filter zu den Kategorien werden auf der Übersichtsseite aller Downloads automatisch hinzugefügt.

### Beschlüsse

[_Zur Videoanleitung_](https://jliberale.sharepoint.com/:v:/s/Bundesvorstand/EW1CSx35mH5OnPliscjC-iIB4ovvM_R5aFbwpMjCXHAP2A?e=WZIU9C)

Geht dafür im Backend auf den Menüpunkt _Beschlusssammlung_. Hier findet ihr alle Beschlüsse, die eingepflegt sind und könnt diese verwalten. Hier hat sich im Vergleich zum alten Regiosystem im Wesentlichen nichts geändert.

Einen neuen Beschluss könnt ihr erstellen wie in der Vergangenheit. Außerdem könnt ihr diesen mit dem WordPress-Editor und Elementor gestalten. Ferner könnt ihr Beschlüsse über das Beschlussorgan und das Sachgebiet kategorisieren. Im Menü auf der rechten Seite könnt ihr außerdem optional einen Textauszug definieren, der den Beschluss zusammenfasst.

**Wichtig**: Bei Beschlüssen gibt es zwei Arten von Daten. Es gibt das Datum der Veröffentlichung (ab diesem ist der Termin für Nutzer sichtbar) und das Beschlussdatum. Beide Daten sind Pflichtangaben zur Veröffentlichung.

Beschlusssammlung bearbeiten: Um das Design der Beschlusssammlung zu bearbeiten, z.B. das Titelbild, müsst ihr auf die entsprechende Archivseite navigieren. Dazu geht auf die Domain (z.B. [www.julis.de/beschlusssammlung](http://www.julis.de/beschlusssammlung)) und klickt unter _Mit Elementor_ bearbeiten auf _Archiv_. Dort könnt ihr dann z.B. ein Foto im Kopf der Seite einfügen. Wählt dazu unten links den Navigator in Elementor aus und tauscht das Hintergrundbild im ersten Abschnitt aus.
