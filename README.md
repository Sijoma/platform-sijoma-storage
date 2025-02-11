# platform-sijoma-encryption

## How to use:

1. kind create cluster
2. Install crossplane

```bash
helm repo add \
crossplane-stable https://charts.crossplane.io/stable
helm repo update

helm install crossplane \
crossplane-stable/crossplane \
--namespace crossplane-system \
--create-namespace
```
# platform-sijoma-storage
