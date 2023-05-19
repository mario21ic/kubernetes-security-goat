helm repo add falcosecurity https://falcosecurity.github.io/charts
helm repo update
helm install falco --set tty=true falcosecurity/falco

stern --init-containers falco
kubectl get pods --selector app.kubernetes.io/name=falco

stern falco
kubectl run --rm --restart=Never -it --image=madhuakula/hacker-container -- bash
# uptime
# cat /etc/shadow
