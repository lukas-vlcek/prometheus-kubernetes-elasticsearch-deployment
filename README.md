
You have to define where the Prometheus server will be available via `PROMETHEUS_URL` env. Example:

````
oc new-app -f prometheus.yaml -p PROMETHEUS_URL=prometheus.ec2-34-229-231-234.compute-1.amazonaws.com
````


