# rabbitmq-cluster

oc apply -f rabbitmq-template.yaml
oc port-forward rabbitmq-0 15672:15672
http://localhost:15672/
