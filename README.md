# Prereqisite
- install kubectl
- install minikube
# Apply the configuration file
`kubectl apply -f client-node-port.yaml`

`kubectl apply -f client-deployment.yaml`

# Verification
`kubectl get pods`

`kubectl get deployments`

# Inspect the pods information
`kubectl describe pods <pod-name>`

# Change the image of the deployment
`kubectl set image deployment/client-deployment client=phquoc25/multi-client:v2`