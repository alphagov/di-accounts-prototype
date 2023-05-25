## TODO

Write up a readme explaining what this is and how to install it.

Eg: I ran:

```
gds aws di-account-dev -- aws cloudformation create-stack --stack-name di-accounts-prototype \
--template-body file://$(pwd)/deploy/template.yaml \
--region eu-west-2 --capabilities CAPABILITY_NAMED_IAM CAPABILITY_AUTO_EXPAND \
--parameters ParameterKey=VpcStackName,ParameterValue="vpc-enhanced"
```
