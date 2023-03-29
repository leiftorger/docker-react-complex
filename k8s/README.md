# For Google Kubernetes engine

## Run commands in [console](https://console.cloud.google.com/)

```
gcloud config set project docker-react-complex
```

```
gcloud config set compute/zone europe-north1-a
```

```
gcloud container clusters get-credentials docker-react-complex
```

```
kubectl create secret generic pgpassword --from-literal PGPASSWORD=<thesecretpassword>
```

```
curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/master/scripts/get-helm-3
chmod 700 get_helm.sh
./get_helm.sh
```

```
helm repo add ingress-nginx https://kubernetes.github.io/ingress-nginx
helm install my-release ingress-nginx/ingress-nginx
```
