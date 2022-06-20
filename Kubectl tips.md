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
### Inspecting pod resource usage
#### Kubernetes Metrics Server
An add-on to use kubectl top
#### Kubectl top
```Command
kubectl top pod --sort-by cpu/name/memory
kubectl top pod --selector app=metrics-test
kubectl top node
# View data about resourse usage
```
