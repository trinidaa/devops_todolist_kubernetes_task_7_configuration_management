### The instructions on how to deploy daemonset.yml and cronjob.yml to the cluster.
```bash
   kubectl apply -k .\.infrastructure\
```
### Instructions on how to validate the changes
```bash
    kubectl exec -it -n todoapp todoapp-58b4c86644-dk9jr  -- printenv
```