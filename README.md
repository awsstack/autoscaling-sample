# AWS EC2 Autoscaling Sample

This AWS Cloudformation template defines basic autoscaling policy
with evening and morning scheduled actions. This template can be used as a
basis point for simple cost efficient development environment which starts
in the morning and scales in to zero in the evening.

![architecture](images/arch.png)

# Launch the stack

[![cloudformation-launch-button](images/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-2#/stacks/new?stackName=Production&templateURL=https://s3.amazonaws.com/awsstack-autoscaling-sample/template.yml)
