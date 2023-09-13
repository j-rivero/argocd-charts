# RMF argocd installation

```
helm dependency update
helm install argocd --create-namespace . -n argocd --values values.yml
```
