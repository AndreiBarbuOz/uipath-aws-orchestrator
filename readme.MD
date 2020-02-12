# UiPath Orchestrator templates for AWS

```cmd
aws cloudformation create-stack --stack-name orch-deploy --template-body file://orch-single-node.yaml --parameters file://orch-single-node-params.json --capabilities CAPABILITY_IAM
```


```cmd
aws cloudformation validate-template --template-body file://orch-single-node.yaml  
```

