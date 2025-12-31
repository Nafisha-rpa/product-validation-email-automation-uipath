# product-validation-email-automation-uipath
UiPath RPA project that validates product codes from Google Sheets and sends automated email notifications based on validation results.
# Product Validation and Email Automation – UiPath RPA

## Tool
UiPath Studio

## Description
This UiPath RPA project reads product or customer codes from Google Sheets, validates them using business rules, and sends automated email notifications based on the validation result.

## Process Flow
1. Read product/customer data from Google Sheets
2. Store data in a DataTable
3. Iterate through each record
4. Validate the submitted code
5. If valid, send a success email
6. If invalid, handle the exception accordingly

## Activities Used
- Google Sheets Integration
- DataTable
- For Each Row
- If Condition
- Send Email
- Exception Handling

## Deployment

The automation was published as a solution and successfully activated using UiPath Orchestrator and Integration Service.

## Status
Executed successfully with logs captured in Orchestrator.

<img width="1254" height="536" alt="Screenshot 2025-12-30 192942" src="https://github.com/user-attachments/assets/23c8962a-1d15-475a-91cb-22f11eb7b296" /

<img width="1698" height="801" alt="Screenshot 2025-12-30 193219" src="https://github.com/user-attachments/assets/7e4599a8-7a6d-41c1-89b2-4da3cb75a6bb" />


