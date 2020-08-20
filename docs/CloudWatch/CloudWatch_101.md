# CloudWatch 101

## What is CloudWatch

Amazon CloudWatch is a monitoring service for AWS cloud resources and the applications you run on AWS.

## Benefits

* Observability on a single platform across applications and infrastructure
* Easiest way to collect metrics in AWS on-premise
* Imprive operational performance and resources optimization
* Get oeprational visibility and insights
* Derive actionable insights from logs

## How it works

* Collect
* Monitor
* Act
* Analyse

## Features

### Listing

#### Collect

Collect logs from

* EC2 instances
* On-premise servers
* VPC Flow Logs
* AWS CloudTrail
* AWS Lambda
* Other AWS Services

#### Built in metrics

* EC2
* DynamoDB
* S3
* ECS
* Lambda
* APi Gateway
* and more than 70 AWS services

#### Custom metrics

* publish metrics using AWS CLI or an API
* Standard resolution with one-minute granularity

#### Collect and aggregate container metrics

* CPU
* RAM
* Disk
* Network

Automatic Dashboards
Set alarms on metrics

#### Unified operational view with dashboards

* A single view for selected metrics and alarms
* Multiple AWS accounts and multiple regions
* ...

#### High resolution alarms

Amazon CloudWatch alarms allow you to srt a threshold on metrics and trigger an action

* Watch a single metric or the result of a match expression
* Perform actions based on the value of metrics
  * Send a notification to an SNS topic
  * Auto Scaling action
  * EC2 Action (Stop, Terminate, Reboot or Recover)
* Add alarms to dashboard to visualize them

#### Logs and metrics correlation

Amazon CloudWatch also makes it wasy to correlate metrics and logs.

* Manage logs and metrics in a single platform
* Use metric filters to convert logs to metrics

#### Anomaly Detection

When you enable anomaly detection for a metric, ClodWatch applies machine learning algorithms to the metric's past data to create a model of the metric'S expected values.

* Create alarms that auto-adjust thresholds based on natural metric patterns
* Alarm when the metric value is above or below the band, or both
* Visualize metrics with anomaly detection bands on dashboards

#### ServiceLens

You can use CloudWatch ServiceLens to visualize and analyze the health, performance ans availability of your applications in a single place.

* Integrates CloudWatch witch AWS X-Ray to provide an ent-to-end view of your application
* A service map displays your service endpoints and resources as "nodes" and highlite the traffic, latency and errors for each node and its connections
* You can choose a node to see details

#### Synthetics

Run tests on your endpoints everyminute, 24x7 and alerts you as soon as your application endpoints don't behave as expected.

* View of your customers' experience
* Configureable scripts
* Run once
* Run on schedule
* Check availability and latency
* Store load time data
* Store screenshots

#### Auto Scaling

Auto Scaling helps you automate capacity and resource planning.

* Set a threshold to alarm on a key metric and trigger an automated Auto Scaling action

#### Automation

CloudWAtch Alarms can send a notification to SNS, from there you can trigger

## Analyse

### Log analytics

* You can instantly begin writing queries with aggregations, filters and 

### Contributor Insights

Analyze time-series data to provide a view of the top contributors influencing system performance.

* Runs continuously with needing user interventions
* Understand who or what is impacting your system
* Evaluate patterns in structured log events
* Add to CloudWatch alarms

## Limits to know

* Up to one second intervall
* up to 15 months of historic data
