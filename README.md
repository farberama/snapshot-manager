# snapshot-manager
Demo project to manage AWS EC2 instance snapshots

## About

This project is a demo that uses boto3 to manage AWS EC2 instance snapshots.
 
## Configuring

snaps uses the configuration file created by the AWS cli:

`aws configure --profile snaps`

## Running 

`pipenv run pythong snaps/snaps.py <command>
<subcommand><--project=PROJECT >`

*commad* is instances, volumes or snapshots
*subcommand* is snapshot, list, start, or stop
*project* is instances' Project tag value and is optional