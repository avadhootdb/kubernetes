Kubernetes
https://www.youtube.com/watch?v=dnO02PKNLzE

Designing Kubernetes from scratch. (Considering the setup is already active on-prem)
1) level 0 -- requirement gathering.
List of microservices.
Teams that are working on microservices -- define namespaces accordingly.
Segregate the microservices into less important, medium, and critical categories.
Identify the resources -- what info can we get from which service/tool (existing metrics from prometheus/grafana).
Cost -- Estimate the cost, note all this things in onboarding sheet
End Goal - Prepare onboarding sheet

3) Level 1 -- Proof of concept
Take 5 services from the less imp, medium, and critical categories each and create one Kubernetes cluster.
Create a deployment ( stateful set, daemon set ), create Kubernetes services, and create an ingress and an ingress controller.
Do testing.
End Goal - Verify the Readiness

4) Level 2 -- Set up dev cluster.
End Goal - Dev Environment is Ready

5) Level 3 -- Set up staging environment.
End Goal - Verify the Readiness

5) Level 4 - Onboarding Prod
End Goal - Verify the Readiness

6)Level 5 - Scaling Production
End Goal - HA Multi Zone, Multi Region
