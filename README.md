# Setup all helm charts

```sh
kustomize build . --enable-helm | kubectl apply --server-side -f -
```

openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout tls.key -out tls.crt -subj "/CN=api.petadoption.local/O=Pet Adoption Services"