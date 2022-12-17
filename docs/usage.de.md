# Nutzung

## Nutzung des Plugins

Die Nutzung des EventList-Plugins ist denkbar einfach. Sobald das Plugin aktiviert ist, erscheint bei Bearbeitung jedes Artikels ein extra Reiter namens "Kontaktperson, Ort, Zeit", wo die verfügbaren Felder bearbeitet werden können. Alle Felder sind optional, d.h. wenn keine Eingabe erfolgt, werden sie auch nicht unter dem Artikel ausgegeben.

![Eingabefelder des EventList-Plugins](assets/images/Eventlist_Plugin_Eingabe.png){ .off-glb }

- In Eventliste anzeigen: Wenn ja, wird der Artikel in der Eventliste angezeigt (wenn ein Wochentag gesetzt ist); Voreinstellung: Ja
- Kontaktperson: Kontaktperson für die regelmäßige Veranstaltung
- E-Mail: E-Mail-Adresse der Kontaktperson
- Telefonnummer: Die Telefonnummer der Kontaktperson
- Zielgruppe: Die Gruppe von Menschen, die mit der Veranstaltung angesprochen werden soll
- Ort: Der Veranstaltungsort
- Wochentag: Der Wochentag der Veranstaltung
- Startzeit: Die Startzeit der Veranstaltung
- Endzeit: Die Endzeit der Veranstaltung
- Kommentar: Hinweise zur Zeit (z.B. 14-tägig)

## Einbindung des Moduls in die Webseite

Das Modul kann entweder in einer von Ihrem Template vorgegebenen Position eingebunden werden oder frei im Inhalt eines Artikels positioniert werden.

Für eine vorgegebene Template-Position wählen Sie die Position in der Liste der verfügbaren Positionen und über den Reiter "Menüzuweisung" die Seiten, auf denen das Modul eingebunden werden soll.

Für eine freie Positionierung geben Sie in der Positions-Box Ihre eigene Bezeichnung ein (z.B. "Regeltermine" wie im Bild zu sehen) und binden Sie die Event-Liste im Artikel dann über den Befehl `{loadposition Regeltermine}` an beliebiger Stelle ein. In diesem Fall empfiehlt es sich, im Reiter "Menüzuweisung" alle Seiten auszuwählen.

![Frei Positionierung des Moduls in einem Artikel](assets/images/Eventlist_Modul_Konfiguration_FreiePositionierung.png){ .off-glb }
