#Create secret
 #kubectl create secret generic pgpassword --from-literal PGPASSWORD=12345sdf

kubectl apply -f k8s

use ingress-nginx NOT kubernetes-ingress


kubectl get nodes
kubectl drain minikube - remove all pods and turn off scheduler
kubectl uncordon minikube - turn on minikube scheduling