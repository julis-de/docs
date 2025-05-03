---
order: 900
---
# 🚚Umzug und Migration

### Vor der Migration / Einrichtung der Seite

Bevor ihr den Umzug eurer Website in Angriff nehmt, solltet ihr euch überlegen, was ihr von euer derzeitigen Seite behalten wollt. Macht dazu am besten ein ausführliches Back-Up. Außerdem erläutern wir euch im folgenden kurz, wie ihr eure Beschlusslage exportiert.

### Export der Beschlusslage

Navigiert im WordPress-Backend auf _Werkzeuge -> Export_. Wählt dort die Beschlusslage aus und klickt auf den Button _Export-Datei herunterladen_. Den Import der Beschlusslage könnt ihr dann nach der Migration zur neuen Seite vornehmen. Die Anleitung dazu findet ihr deshalb im nächsten Kapitel.

**Hinweis**: Bitte beachtet, dass bei anderen Inhaltsseiten (wie Personen) ein Export und Import ggf. nicht so einfach möglich ist wie bei Beschlüssen, weil sich die Felder der dynamischen Inhaltstypen ggf. geändert haben.

### Migration / Umzug der Seite

**Wichtig**: Solltet ihr das **Mietmodell** bei den Jungen Liberalen erworben haben, könnt ihr diesen Schritt **überspringen**. Eure Website wird euch mit **eingerichtetem Theme und Plugins** zur Verfügung gestellt. Solltet ihr lediglich das Theme gekauft haben, so müsst ihr diesen Schritt zusätzlich eigenständig durchführen. Die **inhaltliche Konfiguration** (Import der Beschlusslage, Erstellen von Personen, Seiten etc.) muss in beiden Fällen **von euch selber durchgeführt** werden.

**Wichtig**: Ggf. müsst ihr noch den **Wartungsmodus** im Backend ausstellen.

[_Zur Videoanleitung_](https://mediathek.julis.de/videos/migration-des-regiosystems-auf-wordpress/)_: Umzug der Seite_

[_Zur Videoanleitung:_](https://mediathek.julis.de/videos/anmeldung-login/) _Anmeldung bei WordPress_

Für die Migration benötigt ihr zuerst eine leere WordPress-Installation. Solltet ihr eure bestehende WordPress-Installation nutzen wollen, denkt bitte an ein ausführliches und gut gesichertes BackUp, da im folgenden Prozess alle Daten überschrieben werden.

1. Klickt auf Plugins -> Installieren. Gebt dort in die Suche „WpVivid Backup Plugin“ ein. Dieses findet ihr auch [hier](https://wordpress.org/plugins/wpvivid-backuprestore/). Installiert dieses Plugin.

2. Im Anschluss, aktiviert das Plugin durch einen Klick auf den entsprechenden Button.

3. Wählt das Plugin in der linken Menüleiste aus und scrollt runter zum Tab Hochladen. Klickt auf den Tab und ladet die euch zur Verfügung gestellte Datei hoch.

4. Nach dem Upload klickt auf Wiederherstellen. Im Anschluss bereitet WordPress die Installation vor. Das kann einen Moment dauern.

5. Im Anschluss müsst ihr euch erneut einloggen. Der Log-In findet in der Regel über eure Domain statt mit dem Zusatz „/wp-admin“, d.h. z.B. [www.julis-mallorca.de/wp-admin](http://www.julis-mallorca.de/wp-admin). Nutzt dazu die euch zur Verfügung gestellten Login-Daten.

6. Gebt dann euren vorliegenden Lizenzschlüssel ein und klickt auf Speichern.

Herzlichen Glückwunsch! Eure Seite im JuLi-CD ist jetzt funktionsfähig.

### Import der Beschlusslage

Navigiert im WordPress-Backend auf _Werkzeuge -> Daten importieren_. Wählt dort den _WordPress Importer_ aus. Ggf. muss dieser erst installiert werden, bevor er ausgeführt werden kann. Klickt dann auf ausführen, wählt die von euch exportierte Beschlusslagendatei aus und führt den Import aus.

**Hinweis**: Mit dem neuen Regiosystem unterscheiden wir bei Beschlüssen zwischen dem _Beschlussdatum_ und dem _Veröffentlichungsdatum_. Im alten Regiosystem gab es nur das letztere Synonym für beides. Deshalb muss das _Beschlussdatum_ nach dem Import ggf. manuell gesetzt werden. Solltet ihr das nicht tun wollen, gibt es keine Einschränkung in der Funktionalität, aber das Beschlussdatum ist ggf. nicht auf eurer Website, dafür aber im Backend sichtbar. Das Beschlussdatum lässt sich am besten und effizientesten über die QuickEdit-Funktion setzen.
