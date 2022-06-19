### Imperative commands

### Yaml
use --dry-run flag to run an imperative command without creating an object. 
Combine it with -o yaml to quickly obtain a sample Yaml file you can manipulate
```Command
kubectl create deployment deploymentname --image=nginx --dry-run -o yaml
```
use the Docs: like deployment scrips

### Export Yaml from an object

```Command
kubectl create deployment deploymentname --image=nginx --dry-run -o yaml
```
