# Setup all helm charts

```sh
kustomize build . --enable-helm | kubectl apply -f -
```