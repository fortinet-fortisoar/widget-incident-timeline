# Incident Timeline

Displays a vertical timeline that shows the correlations, alerts and indicators, of an incident record sorted on user-selectable date fields. 

You can add this widget to the view panel of an incident record to view a vertical timeline of the alerts and indicators related to that incident record. The timeline entries are sorted using the date fields, such as Created On, First Seen, Modified On, etc., which are selected by the user.

## Version Information

**Version**: 1.0.0

**Certified**: No

**Publisher**: Fortinet  

**Compatibility**: 7.2.0 and later  

**Applicable**: Reports and View Panel

## Incident Timeline Views

**Incident Timeline Edit View**:

<img src="https://raw.githubusercontent.com/fortinet-fortisoar/widget-incident-timeline/release/1.0.0/docs/media/incident-timeline-edit-view.png" alt="Editing the Incident Timeline Widget" style="border: 1px solid #A9A9A9; border-radius: 4px; padding: 10px; display: block; margin-left: auto; margin-right: auto;">

**Incident Timeline Graph**:

<img src="https://raw.githubusercontent.com/fortinet-fortisoar/widget-incident-timeline/release/1.0.0/docs/media/incident-timeline-graph.png" alt="Incident Timeline Graph" style="border: 1px solid #A9A9A9; border-radius: 4px; padding: 10px; display: block; margin-left: auto; margin-right: auto;">

## Incident Timeline Settings

Provide the following details to customize the Incident Timeline widget to suit your requirements:

| Fields                              | Description                              |
| ----------------------------------- | ---------------------------------------- |
| Incident Timeline Widget Title      | Title of the Incident Timeline graph that you want to display on the records' detail view. Provide a meaningful title that helps users understand the purpose of the widget. |
| Alerts - Place Records Based on     | Select the field based on which the alerts that are correlated with the selected incident record are placed on the timeline. The correlated alert records with the most recent values in the selected field are placed lower on the timeline. For example, if the **Created On** field is selected, then the correlated alerts that have the latest date in the **Created On** field get placed the lowest on the timeline. |
| Indicators - Place Records Based on | Select the field based on which the indicators that are correlated with the selected incident record are placed on the timeline. The correlated indicator records with the most recent values in the selected field are placed lower on the timeline. For example, if the **First Seen** field is selected, then the correlated indicators that have the latest date in the **First Seen** field get placed the lowest on the timeline. |
| Alerts - Fields To Include          | Select the fields that will be displayed on a data card in the timeline when an alert record is expanded. The fields that you select are displayed in the `fieldname:fieldvalue` format. |
| Indicators - Fields To Include      | Select the fields that will be displayed on a data card in the timeline when an indicator record is expanded. The fields that you select are displayed in the `fieldname:fieldvalue` format. |
| Expand Events By Default            | Select this option to expand the indicators' and alerts' data cards by default in the timeline. |
| Alerts - Event Color Field          | Select the field (picklist field) of the alert using whose value the data cards' get highlighted, if the selected field's options contain defined color codes. For example, if you select **Severity**, and if the Severity picklist has defined color codes for its options, then the data cards' get highlighted with the severity that is set for that correlated alert, i.e., the data card of an alert whose severity is set to 'Critical' is highlighted in the 'red' color. |
| Indicators - Event Color Field      | Select the field (picklist field) of the indicator using whose value the data cards' get highlighted, if the selected field's options contain defined color codes. For example, if you select **Reputation**, and if the Reputation picklist has defined color codes for its options, then the data cards' get highlighted with the reputation that is set for that correlated indicator, i.e., the data card of an indicator whose reputation field is set to 'No Reputation Available' is highlighted in the 'light green' color. |


