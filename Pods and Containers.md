### Managing Application Configuration

### Store configuration Data
ConfigMap: kind as ConfigMap, store key-value pairs in yaml file \
Secrets: kind as Secret \
#### ways to pass values
1. ConfigMap and Secrets can be passed to my containers as environmental variables in container SPEC\
2. Mounted volumes

### Monitor Container Health
#### Liveness Probes
Liveness probes allow you to auto determine whether or not a container app is in a healthy state\
Allow tou to customize detection mechinism to be more specific
#### Startup probes
only run at container startup\
determine when the app has successfully start up
#### Readiness probes
Determine when the container is ready to accept requests\
prevent user traffic from being sent until ready
