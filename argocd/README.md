# RMF argocd installation

```
helm dependency update
helm install argocd --create-namespace . -n argocd --values values.yml

# Get the initial password for ArgoCD
kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d
```

For more on ArgoCD, vist their [readthedocs](https://argo-cd.readthedocs.io/en/stable/) page.
