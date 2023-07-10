# Домашнее задание к уроку 3 - Kubernetes


kubectl create ns kubedoom

kubectl config set-context --current --namespace=kubedoom

kubectl apply -f manifest.yaml 

kubectl apply -f pod.yaml

kubectl apply -f deployment.yaml 

kubectl get pod 

(STATUS Running)

kubectl port-forward kube-doom-deployment-xxxxxxxxxx-xxxxx 5900:5900











