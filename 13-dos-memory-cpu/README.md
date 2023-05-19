http://127.0.0.1:1236/

stress-ng --vm 2 --vm-bytes 2G --timeout 30s

kubectl --namespace big-monolith get pod 
kubectl --namespace big-monolith top pod hunger-check-deployment-689bf5d97f-27dch

