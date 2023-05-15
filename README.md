#  lambda in AWS from VSC $ SAM cli

* $ aws configure
...
Default region name: eu-west-3
Default output format: json

* $ sam --version
* $ sam -h

## create lambda form VSC
AWS: Create Lambda SAM Application
select python & folder

## install docker
* $ docker --version

## install extension for aws: aws toolkit and test lambda
* $ sam local invoke

## create the build
* $ sam build

## deploy to aws
* $ sam deploy --guided

## Previewing CloudFormation changeset before deployment
* Deploy this changeset? [y/N]: y