# Was ist EventList für Joomla?

EventList für [Joomla 4](https://www.joomla.de){:target="_blank"} ist ein Joomla!-Paket, das wöchentlich wiederkehrende Veranstaltungen wie Chorproben, Gruppenstunden, etc. automatisch als übersichtliche Liste darstellt und auf die Detail-Beschreibung verlinkt.

![Beispielhafte EventList-Ansicht](assets/images/Portfolio_EventList.png){ .off-glb }

Joomla! EventList ist eine Paketinstallation und besteht aus zwei Erweiterungen:

- Ein Plugin, welches jedem Artikel zusätzliche Felder wie Kontaktperson, E-Mail-Adresse, Telefonnummer, Wochentag, Startzeit, usw. zur Verfügung stellt. Diese Felder werden dann am Ende des Artikels in einer übersichtlichen Infobox angezeigt. Das Plugin kann auch ohne das Modul verwendet werden.
- Ein Modul, welches alle zur Anzeige ausgewählten Artikel als übersichtliche Liste darstellt (siehe Bild). Dieses Modul kann an jeder beliebigen Stelle eingebunden werden und natürlich auch per CSS angepasst werden. Aus der Liste heraus wird auf den Artikel mit der Detailbeschreibung verlinkt. Das Modul benötigt das Plugin!

## Besonderheiten

### EventList PlugIn Besonderheiten

![Infobox unter dem Artikel](assets/images/EventList_Plugin_Ausgabe.png){ style="width:100px", align=right }

- Auswahl, ob ein Artikel in der Event-Liste dargestellt wird oder nicht
- Felder für Kontaktperson, E-Mail-Adresse, Telefonnummer, Zielgruppe und Ort (relevant für die Anzeige im Artikel)
- Weitere Felder für Wochentag, Startzeit, Endzeit, Kommentar (zusätzlich relevant für die Anzeige im Modul EventList)
- Verschiedene voreingestellte Zeitformate: 24h-Format mit oder ohne führender Null, 12h-Format mit oder ohne führender Null
- Alternativ: Frei konfiguierbares Zeitformat
- Regex-basierte Prüfung des Eingabeformats von Start- und Endzeit
- Ausgabe als Infobox am Ende des Artikels (siehe Bild), konfigurierbar mit oder ohne Kopfzeile / Titel 

### EventList Modul Features

- Anzeige aller ausgewählten Artikel als übersichtliche, kompakte Event-Liste
- Möglichkeit, nicht publizierte Artikel in die Event-Liste aufzunehmen (wenn z.B. kein Artikelinhalt zur Verfügung steht, das Event aber dennoch in der Liste angezeigt werden soll)
- Verschiedene voreingestellte Listendarstellungen: Deutsch (fügt das Wörtchen "Uhr" hinzu) oder international
- Alternativ: Frei konfigurierbares Listenformat
- Verlinkung auf die Detailbeschreibung (nur im Falle von bereits publizierten Artikeln)
- Formatierung via eigenem CSS

## Bekannte Fehler

[Diese Fehler](https://github.com/UlricusR/joomla4-eventlist/issues){:target="_blank"} sind mir bekannt. Sollten Sie über weitere Fehler stolpern, können Sie diese an selber Stelle melden.

Da ich Joomla nicht mehr nutze, entwickle ich auch das Plugin nicht mehr weiter.

## Mitmachen

Sollten Sie die Entwicklung weiterführen wollen, herzlich gerne! Es steht alles auf [GitHub](https://github.com/UlricusR/joomla4-eventlist){:target="_blank"} bereit.

Ansonsten freue ich mich über jeden spendierten Kaffee...

[![Spendiere einen Kaffee](assets/images/buymeacoffee_darkbackground.png#only-dark){ .off-glb }](https://www.buymeacoffee.com/ulricus){:target="_blank"}
[![Spendiere einen Kaffee](assets/images/buymeacoffee_lightbackground.png#only-light){ .off-glb }](https://www.buymeacoffee.com/ulricus){:target="_blank"}
