Kubernetes
https://www.youtube.com/watch?v=dnO02PKNLzE

Designing Kubernetes from scratch. (Considering the setup is already active on-prem)
1) level 0 -- requirement gathering.
List of microservices.
Teams that are working on microservices -- define namespaces accordingly.
Segregate the microservices into less important, medium, and critical categories.
Identify the resources -- what info can we get from which service/tool (existing metrics from prometheus/grafana).
Cost -- Estimate the cost

2) Level 1 -- Proof of concept
Take 5 services from the less imp, medium, and critical categories each and create one Kubernetes cluster.
Create a deployment ( stateful set, daemon set ), create Kubernetes services, and create an ingress and an ingress controller.
Do testing. 
