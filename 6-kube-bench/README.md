https://github.com/aquasecurity/kube-bench

kubectl apply -f scenarios/kube-bench-security/node-job.yaml
kubectl apply -f scenarios/kube-bench-security/master-job.yaml

kubectl get jobs
kubectl get pods

kubectl logs -f kube-bench-node-xxxxx


