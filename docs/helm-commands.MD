# Add stable to helm

```sh
helm repo add stable https://charts.helm.sh/stable


helm install repo stable/<chartname> <releasename>

helm search repo stable 

helm pull <chartname>
  
helm package <chartname>

helm uninstall RELEASE_NAME
```
