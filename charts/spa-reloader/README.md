[![Artifact HUB](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/toucan)](https://artifacthub.io/packages/search?repo=toucan)

# Single Page Application Reloader Helm Chart

## Single Page Application Reloader

SPA Reloader provides a Kubernetes Controller that listens to changes in Deployments container image changes,
and informes Single Page Applications via WebSockets.

## Installing the Chart

Install Toucan Software Helm Chat repository

```console
helm repo add toucan https://toucansoft.io/charts
```

To install the chart with the release name `spa` and watching to Deployment `foo` in namespace `bar`:

```console
helm install spa --set deployment.name=foo --set deployment.namespace=bar toucan/spa-reloader
```

## Uninstalling the Chart

To uninstall/delete the `spa` deployment:

```console
helm delete spa
```
