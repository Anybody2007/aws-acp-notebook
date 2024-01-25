**Search for Billing. In the `Billing Preferences` we should enable the `Receive Free Tier Usage Alerts`.** 
- When you are in the Free Tier mode, so that this will send you an email that the free tier mode is ended now.

**Search for Billing. Inside the `Billing Preferences` we should also enable the `Receive Billing Alerts`.** 
- This is where you need to enable, so that you will get the cost notifications.

**SNS - Simple Notification Service**


# Billing Alerts with CloudWatch
- Search for Billing. Inside the `Billing Preferences` we should also enable the `Receive Billing Alerts`.

## Setting up an alert when the usage is more than $20
- Can be setup via `CloudWatch` and only works on `N. Virginia` region.
- Left side bar `Alarms` and then `Billing` section.
- Select `Metric` the `Billing` then `Total Estimated Charge` then select `Currency`
- Give the `Name` for the `Billing Alert` and select the `Period` of time frame. `Threshold Type` should be `Static`, `Greter/Equal` than `Ammount`. In the `Additional configuration` select the `Treat missing data as ignore`.
- `Alarm state trigger` set to `In alarm`. `SNS topic` set to `Create new topic`. Provide the `new-name`. Proved the `Email-Address`.

# Cost Explorer

# AWS Budget

Monthly costs by service