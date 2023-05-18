
curl http://127.0.0.1:1235/v2/
curl http://127.0.0.1:1235/v2/_catalog

curl http://127.0.0.1:1235/v2/madhuakula/k8s-goat-users-repo/manifests/latest
curl http://127.0.0.1:1235/v2/madhuakula/k8s-goat-users-repo/manifests/latest | grep -i env 


