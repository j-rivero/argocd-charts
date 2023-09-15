# RMF harbor installation

```
helm dependency update
helm install harbor --create-namespace . -n harbor --values testing-values.yml
```

For accessing to harbor, checkout the [default passowrd for the admin in the helm documentation](https://github.com/goharbor/harbor-helm)
