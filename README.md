# aws-prometheus-eks

## Check Namespaces exist ?!

```
   kubectl get ns | grep amazon-cloudwatch
   #if not exist 
   kubectl create -f namespace.yaml
```
