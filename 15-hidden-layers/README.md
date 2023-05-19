Analyze hidden layers in Container in Kubernetes Cluster - Kubernetes Goat Scenario 🚀


docker inspect madhuakula/k8s-goat-hidden-in-layers

docker history --no-trunc madhuakula/k8s-goat-hidden-in-layers

alias dfimage="docker run -v /var/run/docker.sock:/var/run/docker.sock --rm alpine/dfimage"
dfimage -sV=1.36 madhuakula/k8s-goat-hidden-in-layers

dive madhuakula/k8s-goat-hidden-in-layers


docker save madhuakula/k8s-goat-hidden-in-layers -o hidden-in-layers.tar
tar -xvf hidden-in-layers.tar
cd 12ac7ba79b886011bb35d15b2cf11b7c958affea0f8835339abd9db2342d9adb
tar -xvf layer.tar
cat root/secret.txt


