# AZURE-AKS



az aks get-credentials --resource-group ResourceGroup-For-ACR --name Cluster-Deploymet-Production --overwrite-existing



# Install ArgocCd
kubectl get secrets -n argocd

kubectl edit secret argocd-initial-admin-secret -n argocd
echo em4tTXdYNTZzRTk0ZHpBLQ== | base64 --decode
kubectl get svc -n argocd
 kubectl edit svc argocd-server -n argocd
