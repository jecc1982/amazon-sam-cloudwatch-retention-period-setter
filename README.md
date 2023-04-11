# sam-cloudwatch-retention-period-setter

This SAM application is based on the https://github.com/aws-samples/amazon-cloudwatch-retention-period-setter

The following modification were made to make deployment easier
* Use SAM instead of CloudFormation
* Drop the support for multiple region
* Trigger lambda every day (instead of CreateLogGroup event)

## Prerequisites

* AWS SAM CLI

## Deployment

```
sam deploy --guided
```