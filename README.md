Modification of [original prometheus.yml file](https://github.com/openshift/origin/blob/1408b096ed8b6a5c0c193987a4be023e16d267b4/examples/prometheus/prometheus.yaml).

You have to define where the Prometheus server will be available via `PROMETHEUS_URL` env. Example:

````
oc new-app -f prometheus.yaml -p PROMETHEUS_URL=prometheus.ec2-34-229-231-234.compute-1.amazonaws.com
````


