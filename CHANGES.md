# Changelog

## v0.9.2

* Fix all the boto3 actions (autoscaling, etc.) so they work. Previously they didn't work because
  credentials weren't correctly passed in. #26

## v0.9.1

* Corrected incomplete error handling and validation of configuration (#22).

## v0.3.0

* Added CloudFormation, VPC, IAM, RDS, SQS, S3

## v0.2.0

* Added Route53

## v0.1.0

* Initial release

## v0.3.0

* Add aws.sqs_sensor which can monitor given sqs queue and trigger aws.sqs_new_message

## v0.4.0

* Add support for handling multiple input_queues to aws.sqs_sensor
