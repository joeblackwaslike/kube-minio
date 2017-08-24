# kube-minio

## Usage
* Create a random token and save as a kubernetes secret:
```bash
kubectl create secret generic minio \
    --from-literal=minio.secret.key=${MINIO_SECRET}
```

* Create minio:
```bash
kubectl create -f .
```
