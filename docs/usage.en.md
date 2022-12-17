# Usage

## Plugin Usage

The usage of the EventList-Plugin is simple and straight-forward. As soon as installed and activated, a new tab called "Contact person, location, time" will appear when editing an article, where the input fields can be edited. All fields are optional, i.e. if a field has no value, it won't be displayed in the info box underneath the article.

![Additional input fields of the EventList Plugin](assets/images/Eventlist_Plugin_Eingabe.png){ .off-glb }

- Show in Event List: If yes, the article is included in the Event List (given it has a weekday); default: yes
- Contact person: The contact person for the recurring event
- E-Mail: E-mail address of the contact person
- Phone: Phone number of the contact person
- Target audience: The group of people targeted at with this event
- Location: The location of the event
- Weekday: The weekday of the event
- Start time: The starting time of the event
- End time: The end time of the event
- Comment: Comment on time (e.g. bi-weekly)

## Integration of the Module in the Website

The module can either be integrated as stand-alone module in a defined module position or it can be positioned freely within an article.

For a pre-defined template position, please choose the position in the list of available positions. Under "Menu Assignment" you can define the pages the module is displayed on.

In case of a free positioning, define a module position name in the module position box (e.g. "regular_events"). Then include the module in any article by writing `{loadposition regular_events}`. It is recommeded to assign the module to "all" pages in the "Menu Assignment" tab.

![Free positioning of the module in an article](assets/images/Eventlist_Modul_Konfiguration_FreiePositionierung.png){ .off-glb }
