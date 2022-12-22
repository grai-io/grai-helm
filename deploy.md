# Deploy Guidelines

1. Increment version in [Chart.yaml](charts/grai-helm/Chart.yaml)

2. Generate package

```
helm package charts/grai-helm
```

3. Update index

```
helm repo index . --url https://charts.grai.io
```

4. Push to github
