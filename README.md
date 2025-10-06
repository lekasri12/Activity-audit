# EX - 4 Auditing Cloud Activity Using AWS CloudTrail
## NAME: LEKASRI G
## REGISTER NUMBER: 212223100025

## Aim

To enable and analyze AWS CloudTrail logs to audit user and resource activities in a cloud environment.

## Requirements
1. AWS Console access
2. CloudTrail service enabled
3. S3 bucket (for storing logs)
4. IAM permissions to view audit logs

## Procedure

### Step 1: Enable CloudTrail
Go to CloudTrail from AWS Console
Click Trails > Create trail
Name: CloudAuditTrail
Apply trail to all regions
Log events:
 - Management events: Read & Write
 - Data events: S3, Lambda (optional)
Create or select an S3 bucket for log storage
Enable CloudWatch Logs integration (optional)

### Step 2: Review Event History
Go to Event history
Filter events by:
- Username (IAM role or user)
- Event name (e.g., CreateBucket, TerminateInstances)
- Date/Time
- Resource type (e.g., S3, EC2)

### Step 3: Download or Export Logs

Use the Download CSV option to export logs
Analyze logs in Excel/Sheets for reporting

## Output:
<img width="1064" height="868" alt="screenshot" src="https://github.com/user-attachments/assets/ee5f67fb-0c2c-4b05-9147-280cebbe6f9b" />


## Result

All AWS user activities, including volume creation, deletion, and permission changes, were successfully audited using CloudTrail.
