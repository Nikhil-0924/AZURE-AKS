# AZURE-AKS



az aks get-credentials --resource-group ResourceGroup-For-ACR --name Cluster-Deploymet-Production --overwrite-existing



# Install ArgocCd
kubectl get secrets -n argocd

kubectl edit secret argocd-initial-admin-secret -n argocd
 base64 --decode
kubectl get svc -n argocd
 kubectl edit svc argocd-server -n argocd

 kubectl create secret docker-registry my-secretone \
  --namespace default \
  --docker-server=acrcontainerregistery.azurecr.io \
  --docker-username=acrcontainerRegistery \
  --docker-password=


  ImagePullSecrets


  wsl --install -d Ubuntu

<img width="959" alt="image" src="https://github.com/user-attachments/assets/d3b1fbd1-a68a-4961-9472-e91e2b71da52">
<img width="959" alt="image" src="https://github.com/user-attachments/assets/a594bc6b-c6cf-4ca2-aac4-7e488fdb71f5">
