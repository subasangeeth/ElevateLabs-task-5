# ElevateLabs-task-5
 ## **Kubernetes App Deployment with Minikube**
 ### _Deploy, expose, and scale an application using Minikube_

> #### STEPS

 Start Minikube > `minikube start`

 Check node > `kubectl get nodes`

 Apply deployment > `kubectl apply -f deploy.yaml`

 Verify pods > `kubectl get pods`

 Apply service > `kubectl apply -f service.yaml`

 Check services > `kubectl get svc`

 Scale replicas > `kubectl scale deployment spring-app --replicas=4`

 Get app URL > `minikube service spring-app --url`

 Verify scaling > `kubectl get pods`

 Verify Deployment > `kubectl get deployments`

 Stop cluster > `minikube stop`

