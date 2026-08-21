# Setup all helm charts

```sh
kustomize build . --enable-helm | kubectl apply --server-side -f -
```