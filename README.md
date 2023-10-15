# helm-charts
my helm charts

example:
```
helm dep update ../landing-page/helm/landing-page/
helm package ../landing-page/helm/landing-page/ -d charts/
helm repo index charts/ --url https://bran-tech.github.io/helm/charts/
```