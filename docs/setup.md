| [Home](../README.md) |
|----------------------|

# Installation

1. To install a widget, click **Content Hub** > **Discover**.

2. From the list of widgets that appears, search for and select **Incident Timeline**.

3. Click the **JSON to Grid** widget card.

4. Click **Install** on the lower part of the screen to begin installation.

# Configuration

## Incident Timeline Settings

Provide the following details to customize the Incident Timeline widget to suit your requirements:

| Fields                              | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|-------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Title                               | Title of the Incident Timeline graph that you want to display on the records' detail view. Provide a meaningful title that helps users understand the purpose of the widget.                                                                                                                                                                                                                                                                                                                                                        |
| Alerts - Place Records Based on     | Select the field based on which the alerts that are correlated with the selected incident record are placed on the timeline. The correlated alert records with the most recent values in the selected field are placed lower on the timeline. For example, if the **Created On** field is selected, then the correlated alerts that have the latest date in the **Created On** field get placed the lowest on the timeline.                                                                                                         |
| Indicators - Place Records Based on | Select the field based on which the indicators that are correlated with the selected incident record are placed on the timeline. The correlated indicator records with the most recent values in the selected field are placed lower on the timeline. For example, if the **First Seen** field is selected, then the correlated indicators that have the latest date in the **First Seen** field get placed the lowest on the timeline.                                                                                             |
| Alerts - Fields To Include          | Select the fields that will be displayed on a data card in the timeline when an alert record is expanded. The fields that you select are displayed in the `fieldname:fieldvalue` format.                                                                                                                                                                                                                                                                                                                                            |
| Indicators - Fields To Include      | Select the fields that will be displayed on a data card in the timeline when an indicator record is expanded. The fields that you select are displayed in the `fieldname:fieldvalue` format.                                                                                                                                                                                                                                                                                                                                        |
| Expand Events By Default            | Select this option to expand the indicators' and alerts' data cards by default in the timeline.                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Alerts - Event Color Field          | Select the field (picklist field) of the alert using whose value the data cards' get highlighted, if the selected field's options contain defined color codes. For example, if you select **Severity**, and if the Severity picklist has defined color codes for its options, then the data cards' get highlighted with the severity that is set for that correlated alert, i.e., the data card of an alert whose severity is set to 'Critical' is highlighted in the 'red' color.                                                  |
| Indicators - Event Color Field      | Select the field (picklist field) of the indicator using whose value the data cards' get highlighted, if the selected field's options contain defined color codes. For example, if you select **Reputation**, and if the Reputation picklist has defined color codes for its options, then the data cards' get highlighted with the reputation that is set for that correlated indicator, i.e., the data card of an indicator whose reputation field is set to 'No Reputation Available' is highlighted in the 'light green' color. |

| [Usage](./docs/usage.md) |
|--------------------------|