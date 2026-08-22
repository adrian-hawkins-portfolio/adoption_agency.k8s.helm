# Setup all helm charts

```sh
kustomize build . --enable-helm | kubectl apply --server-side -f -
```

openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout tls.key -out tls.crt -subj "/CN=api.petadoption.local/O=Pet Adoption Services"

hosts
```txt
127.0.0.1   jenkins.minikube.local
127.0.0.1   docker.minikube.local
127.0.0.1   pet-service.minikube.local
127.0.0.1   pgadmin.minikube.local
127.0.0.1   grafana.minikube.local
127.0.0.1   rabbitmq.minikube.local
127.0.0.1   minio.minikube.local
127.0.0.1   s3.minikube.local
127.0.0.1   example.local
127.0.0.1   minikube.nginx.local
```