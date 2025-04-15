# Health Monitoring Dashboard

A simple, offline-first health monitoring dashboard designed to track medication, symptoms, and daily health metrics for recovery.

## Features

- **Offline-First**: All data is stored in the device's local storage
- **Medication Tracking**: Monitor medication schedules and adherence
- **Symptom Monitoring**: Track physical symptoms and severity
- **Health Metrics**: Record bowel movements, fluid intake, meals, sleep, and activity
- **Mental Status**: Quick tests for cognitive function
- **Optional Google Sheets Sync**: Data can be synced to Google Sheets when connectivity is available

## How to Use

1. Simply open the `healthmonitor.html` file in any modern web browser (Chrome, Safari, Firefox)
2. Data will be saved to the device's local storage automatically
3. The app will work fully offline - no internet connection required

## For Caregivers

- Each device maintains its own data in local storage
- To view data on another device, you can enable Google Sheets sync when internet is available
- Toggle between local-only and Google Sheets mode using the button at the top of the dashboard

## Important Notes

- Data saved to local storage stays on the device where it was recorded
- Clearing browser data or using private/incognito mode will prevent data from being saved
- For persistent tracking across multiple devices, use the Google Sheets sync feature

## Technical Details

- No installation required - just open the HTML file
- No server needed - everything runs in the browser
- Works on mobile phones, tablets, and desktop computers
- Daily reset occurs at midnight
