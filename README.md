# linux-agent-ecs-task

This repo provides an AWS Elastic Container Service (ECS) task definition template
to run the Threat Stack Linux Containerized agent as an EC2 task.

The JSON file has to be edited to set the deployment key, rule sets, as well 
as the Task Role and Task Execution Role ARNs.

The modified template can then be pasted into the "Create new Task Definition"
page in the "Configure via JSON" field. Then, the task is ready to be deployed as
an EC2 Daemon Service to monitor all EC2 nodes in an ECS cluster.
