# helm-charts
my helm charts

## Build Charts

```sh
helm dep update ../landing-page/helm/landing-page/
helm package ../landing-page/helm/landing-page/ -d charts/
helm repo index charts/ --url https://bran-tech.github.io/helm/charts/

helm dep update ../poste-io/
helm package ../poste-io/ -d charts/
helm repo index charts/ --url https://bran-tech.github.io/helm/charts/

```

## Install Chart
```sh
helm repo add bran-tech https://bran-tech.github.io/helm/charts/
helm repo update
helm upgrade --install mail bran-tech/poste-io
```
