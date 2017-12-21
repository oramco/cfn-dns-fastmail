# FastMail DNS Record Setup
Setup DNS to use FastMail for EMail

## Prerequisites
[AWS CLI](http://docs.aws.amazon.com/rekognition/latest/dg/setup-awscli.html)
A fastmail account, and adding the appropriate domain and alias records to the fastmail config.

## Setup
Run in console and set params AdHoc, or add required parameters to CLI script as appropriate for your domain

```
aws cloudformation create-stack --stack-name aPrimaryDNSFastMail --template-body file://./cfn-dns-fastmail.yaml
```
