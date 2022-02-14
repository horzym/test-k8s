# test-k8s

### Instalation
```
helm upgrade --install nginx  . -f values-prod.yaml
```
### Check syntax or manifests

```
helm upgrade --install nginx  . -f values-prod.yaml --dry-run
or
helm template nginx  . -f values-prod.yaml --dry-run
```
