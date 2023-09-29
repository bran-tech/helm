# helm-charts
my helm charts

example:
```
helm package ../landing-page/helm/landing-page/ -d charts/
helm repo index charts/ --url https://bran-tech.github.io/helm-charts/
```