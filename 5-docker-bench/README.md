kubectl apply -f scenarios/docker-bench-security/deployment.yaml
kubectl get pods

kubectl exec -it docker-bench-security-xxxxx -- sh
cd docker-bench-security
sh docker-bench-security.sh





