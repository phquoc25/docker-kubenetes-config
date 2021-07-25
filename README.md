# Prereqisite
- install kubectl
- install minikube
# Apply the configuration file
`kubectl apply -f client-node-port.yaml`

`kubectl apply -f client-deployment.yaml`

# Verification
`kubectl get pods`

`kubectl get deployments`