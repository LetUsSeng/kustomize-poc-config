# kustomize-poc-config


## Deploy to Dev
```bash
kubectl apply -k nginx/overlays/dev --wait
```

## Deploy to Pord
```bash
kubectl apply -k nginx/overlays/prod --wait
```

## See what you are goind to deploy
```bash
kustomize build nginx/overlays/dev
```