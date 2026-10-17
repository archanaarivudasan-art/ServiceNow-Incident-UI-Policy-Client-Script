# ServiceNow Incident Management Customization

## Project Overview
This project enhances the Incident Management module in ServiceNow using Client Scripts and UI Policies to improve field validation, automate incident values, and control user interactions.

## Features

### Client Scripts
- **Prevent State Change via List Edit:** Prevents users from changing incident state directly through list editing.
- **Prevent Save if Assigned To Is Missing:** Validates the Assigned To field before an incident can be submitted.
- **Auto Set Urgency for High Impact:** Automatically adjusts urgency based on the incident's impact.

### UI Policy
- **High Impact Control:** Applies conditional field behavior when an incident's impact is high.

## Technologies Used
- ServiceNow
- JavaScript
- Client Scripts
- UI Policies
- XML

## Repository Contents
The XML files contain exported ServiceNow customization records.

## Purpose
To demonstrate ServiceNow form customization, client-side validation, conditional field behavior, and incident workflow improvements.
