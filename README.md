# google-analytics-auditor
This will become a public Add-on for Google Spreadsheets. It is a Google Apps Script (GAS) that connects to the [Google Analytics Management API](https://developers.google.com/analytics/devguides/config/mgmt/v3/) and pulls down information related to Goals, Filters, and View settings.

**Feature Requests**
 - add additional reports

**Bugs**
 - add spinner on sidebar for waiting
 - if there is an error, it shouldn't create the sheet (throw an error in goals header)
 - remove e.preventDefault()

**Prior to launch**
 - document code
 - review [UI Style Guide for Add-ons](https://developers.google.com/apps-script/add-ons/style)
 - add try/catches in all api calls 

**Add to docs**
 - add all 20 goal steps?