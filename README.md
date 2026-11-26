# aws-cloudwatch-ec2-monitoring
Monitors EC2 instance CPU utilization using Amazon CloudWatch. Sends email notifications through Amazon SNS when average CPU usage exceeds 70% for the configured evaluation period. Helps identify high CPU usage and troubleshoot server performance.
# AWS CloudWatch EC2 Monitoring

## Project Overview
This project demonstrates how to monitor an Amazon EC2 instance using AWS CloudWatch and configure email alerts using Amazon SNS.

## AWS Services Used
- Amazon EC2
- Amazon CloudWatch
- Amazon SNS (Simple Notification Service)
- AWS Management Console

## Tasks Completed

### 1. EC2 Monitoring
- Selected the running EC2 instance.
- Located the CPUUtilization metric in CloudWatch.
- Viewed CPU usage through the CloudWatch metrics graph.

### 2. CloudWatch Alarm
- Created an alarm named `EC2-High-CPU-Alarm`.
- Configured the statistic as Average.
- Set the monitoring period to 5 minutes.
- Configured the threshold to greater than 70%.

### 3. SNS Email Notifications
- Created SNS topic: `CloudWatch-CPU-Alerts`.
- Added an email subscription.
- Confirmed the email subscription.

### 4. Alarm Verification
- Verified the CloudWatch alarm in the All alarms dashboard.
- Configured email notifications for high CPU utilization.

## Project Outcome
Successfully configured EC2 CPU monitoring with CloudWatch and email notifications through SNS.

## Skills Demonstrated
AWS CloudWatch | EC2 Monitoring | SNS | Cloud Monitoring | Alarm Configuration | Troubleshooting

## Screenshots
uploaded screenshots showing:
- CPUUtilization graph.
- CloudWatch alarm configuration.
- Created alarm in All alarms.
- SNS topic and confirmed subscription.
<img width="1657" height="960" alt="sns confirmation" src="https://github.com/user-attachments/assets/d5f4eab1-3c44-4573-8fba-5b859e1c865c" />
<img width="1458" height="960" alt="CPU Utilization graph" src="https://github.com/user-attachments/assets/193721a0-e4d7-4d7b-94f1-cb2f381b74e3" />
<img width="1596" height="960" alt="alarm created" src="https://github.com/user-attachments/assets/08fa381e-d3db-41f3-88fd-d48a51a90ae5" />
<img width="1527" height="960" alt="alarm configuration" src="https://github.com/user-attachments/assets/d8b54c92-0655-4399-8403-b841e38ed5e2" />

