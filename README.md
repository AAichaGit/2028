#To obtain the Kubernetes endpoint that Argo CD uses to deploy the app, you can run the following command to get the details of the Argo CD API server and the Kubernetes cluster configuration:#
```
kubectl config view --minify -o jsonpath='{.clusters[0].cluster.server}'
```
