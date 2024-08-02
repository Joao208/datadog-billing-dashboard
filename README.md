# Datadog Billing Dashboard - JSON Import

This repository contains a pre-configured Datadog dashboard and a collection of monitors, ready to be imported and used. The goal is to simplify monitoring setup for your applications by providing a predefined set of graphs, metrics, and monitors.

## Contents

- `dashboard.json`: JSON file containing the complete dashboard configuration.
- `monitors/`: A folder containing multiple monitor configurations that can be imported into Datadog.

## How to Use

### Prerequisites

- An active Datadog account
- Necessary permissions to create or edit dashboards and monitors in Datadog

### Importing the Dashboard

1. Download the `dashboard.json` file from this repository.

2. Log in to your Datadog account and navigate to the Dashboards section.

3. Click on "New Dashboard" and select "Snap widgets into place on a grid."

4. Go to the dashboard settings and click on "Import dashboard JSON..."

5. Upload the downloaded `dashboard.json` file or paste the JSON content directly.

6. Click "Import" to add the dashboard to your account.

### Importing Monitors

1. Navigate to the `monitors/` folder in this repository and download the desired monitor JSON files.

2. In Datadog, go to the Monitors section.

3. Click on "New Monitor" and then on "Import monitor JSON..."

4. Upload the JSON file for the monitor you want to import.

5. Repeat for any additional monitors as needed.

### Customization

After importing the dashboard and monitors, you can customize the graphs, metrics, and alerts according to your needs. This can include adding new widgets, adjusting filters, modifying time ranges, or tweaking alert conditions.
