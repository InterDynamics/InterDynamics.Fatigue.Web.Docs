# Assessments

Once the user’s group has been saved, the user can add assessments. An assessment is the work schedule the user wishes to analyse.

## Assessment view

Saved assessments can be shown as cards or as a table.

Users can toggle between views by selecting:

- **Table View**
- **Card View**

<!-- IMAGE PLACEHOLDER: Assessments list/cards -->
![Assessments view placeholder](assets/placeholders/assessments-view.png)

## Create an assessment

1. Select **Assessments** from the left-hand menu
2. Select **Add New Assessment**
3. Enter an assessment name and optional description
4. Select **Save**

<!-- IMAGE PLACEHOLDER: Create assessment dialog -->
![Create assessment placeholder](assets/placeholders/create-assessment.png)

## Enter a work schedule

To enter a schedule, select **Edit Schedule**.

Users can either create a schedule manually or import one.

### Create a work schedule

1. Select the schedule actions menu
2. Select **Add User**
3. Enter a **User ID** such as a name or number
4. Save the user
5. Select the schedule actions menu again
6. Select **Add Shift**
7. Enter the shift start time and end time using the calendar control or direct text entry
8. Continue adding shifts until the schedule is complete

<!-- IMAGE PLACEHOLDER: Schedule editor -->
![Schedule editor placeholder](assets/placeholders/schedule-editor.png)

### Import a work schedule from file

Supported file types are:

- `.csv`
- `.fqw`

The file must contain these required columns at minimum:

- ID or Name
- Shift Start Time and Date
- Shift End Time and Date

To import a schedule:

1. Select the schedule actions menu
2. Select **Import Schedule**
3. Select a schedule file
4. Choose the file and select **Open**
5. Check whether the columns were assigned automatically
6. If needed, select **Define columns**
7. Select **Import** to overwrite the schedule, or **Import Append** to add to it

<!-- IMAGE PLACEHOLDER: Import schedule dialog -->
![Import schedule placeholder](assets/placeholders/import-schedule.png)

#### Define columns

If columns do not automatically assign:

1. Select the arrow on the first unassigned column to view a sample
2. Select **Assign to internal column**
3. Choose the correct field
4. Repeat until **ID/Name**, **Start**, and **End** fields are assigned
5. Select **Verify**

<!-- IMAGE PLACEHOLDER: Define columns screen -->
![Define columns placeholder](assets/placeholders/define-columns.png)

### Paste a work schedule from clipboard

Clipboard data must contain the same required columns as an imported file.

To paste a schedule from the clipboard:

1. Copy the required data from a spreadsheet
2. Select the schedule actions menu
3. Select **Paste Schedule**
4. Re-paste from clipboard if needed
5. Confirm whether the first row should be used as column headers
6. Assign **ID/Name**, **Start**, and **End** if required
7. Select **Verify**
8. Select **Import** to overwrite, or **Import Append** to add to the schedule

!!! note
    Mozilla Firefox may require a second paste action during the paste-from-clipboard process.

<!-- IMAGE PLACEHOLDER: Paste from clipboard screen -->
![Paste schedule placeholder](assets/placeholders/paste-schedule.png)

### Quick entry

Quick Entry allows an individual user to quickly enter their shift details.

1. Select **Quick Entry** from the left menu under **Inputs**
2. Enter the work start time
3. Enter the work end time
4. Select **Save**

!!! note
    Display and input vary slightly between desktop, Android, and iPhone.

<!-- IMAGE PLACEHOLDER: Quick Entry screen -->
![Quick Entry placeholder](assets/placeholders/quick-entry.png)

## Consolidation assessment

Users with manager privileges can merge individual work schedules into one consolidated work schedule. The consolidated schedule is then added to the assessment list.

1. Select the top-right actions menu
2. Select **Consolidate Assessments**
3. A new entry appears in the assessments list
4. Rename the assessment to something meaningful, such as `Consolidated March 2024`
5. Open the consolidated assessment to edit it if needed

This feature allows managers to analyse all work schedules together and export a consolidated work schedule for FAID Quantum desktop analysis.

!!! note
    Consolidation Assessment is an additional FAID Quantum Web App feature. Contact InterDynamics to discuss access.

<!-- IMAGE PLACEHOLDER: Consolidation workflow -->
![Consolidation assessment placeholder](assets/placeholders/consolidation-assessment.png)

## Analyse schedule

Once the schedule has been entered:

1. Select the schedule actions menu
2. Select **Analyse Schedule**
3. Review the analysis details
4. Check the FAID and KSS tolerance levels
5. Check the analysis start date
6. Select **Submit**

!!! warning
    The tolerance levels you select are your responsibility.

!!! note
    Seven full days of prior work history are required for accurate fatigue scores. Ensure seven full days of work history are provided before the analysis start date.

<!-- IMAGE PLACEHOLDER: Analyse schedule dialog -->
![Analyse schedule placeholder](assets/placeholders/analyse-schedule.png)