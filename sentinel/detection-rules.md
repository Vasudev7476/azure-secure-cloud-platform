# Sentinel Detection Rules

Example rule to detect Azure resources deletion:

AzureActivity
| where operationNameValue contains "Delete"
