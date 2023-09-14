# RMF harbor installation

```
helm dependency update
helm install harbor --create-namespace . -n harbor --values testing-values.yml
```
