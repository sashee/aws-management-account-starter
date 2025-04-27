## Prerequisites

* Turn on budget alarms: https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html#turning_on_billing_metrics
* Enable Organizations
* Deploy to the us-east-1 region

## Inputs

* BudgetLimit: Alarm limit for forecasted costs

## Contents

* CloudTrail multi-region organization trail to an S3 bucket
* Notification for root account login
* Notification for console sign-in
* Notification for access denied errors
* Budget alarm
