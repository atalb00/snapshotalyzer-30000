# snapshotalyzer-30000
Demo Project to manage AWS EC2 Instances

## About

This project is a demo, and uses boto3 to manage AWS EC2 instance snapshots.

## Configuring

shotty uses the confirugation file created by the AWS cli. ex.

`aws configure --profile shotty`

## Running

`pipenv run python shotty\shotty.<command> <subcommand> <--project=PROJECT>`

*command* is instances, volumes, snapshots
*subcommand* depends on command
*project* is optional
