# Configuration

## Plugin Configuration

Please active the Plugin after installation (*Extensions - Plugins*).

![Plugin Configuration](assets/images/EventList_Plugin_Konfiguration.png){ .off-glb }

You can limit the Plugin to articles of certain categories. Furthermore, you can define whether or not child categories of the selected categories should be included.

You can configure the time format. This choice will determine how your starting and end time will be formatted during data entry in the backend. If the entered format does not match this choice, an error message will be issued.

The following pre-defined formats are available:

- 24h format with leading zero, e.g. 09:00
- 12h format with leading zero, e.g. 09:00 AM
- 24h format without leading zero, e.g. 9:00
- 12h format without leading zero, e.g. 9:00 AM
- Free format (not recommended!): A separate text field will appear, where you can enter a Regex term. Please make sure that the time formatted according to this Regex term is recognized as valid time by PHP’s date function, otherwise it will not be possible to save the event infos.

Finally, you can select whether or not the InfoBox is displayed with a title (default: "Info") or not.

## Module Configuration

![Module Configuration](assets/images/EventList_Modul_Konfiguration.png){ .off-glb }

### Parameters

The following parameters are available for Module configuration (Extensions - Modules):

- Include non-published articles: Includes articles that have the necessary fields filled, but are not published yet (e.g. because they are not finalized); default: no
- Category: Selection of categories, for which articles should be included in the event list; if empty, all categories are included
- Week starts: Determines whether the Event List starts Sunday or Monday; default: Sunday
- Template: Selection of the representation of the Event List; International: no local strings like „Uhr“; German: the local string „Uhr“ is appended to the time; Free: fully configurable
![Module configuration for free time format](assets/images/Eventlist_Modul_Konfiguration_FreiesTemplate.png){ style="width:100px", align=right }
- If fully configurable, further fields will appear:
    - Time separator: String separating starting and end time
    - After time: String after the time
    - Before comment: String before the comment
    - After comment: String after the comment
    - Before title: String before the title

### System of Fully Configurable Output

Starting time`<time separator>`End time`<after time>` `<before comment>`Comment`<after comment>` `<before title>`Title

Example:

6:30 PM` to `7:30 PM`(empty)` ` (`except for school holidays`)` `: `Choir rehersal
