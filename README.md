# Satellite Applications Catapult - Helm charts for Kubernetes

This repository stores Helm chart tarballs authored by the Satellite Applications Catapult. Actual development of these Helm charts takes place in the organization's [Helm chart repo](https://github.com/SatelliteApplicationsCatapult/helm-charts).

## Using charts in this repo

Make Helm aware of the [Satellite Applications Catapult Helm chart repository](https://satelliteapplicationscatapult.github.io/helm-charts/), so you will be able to install charts from it without having to use a long URL name:

```bash
helm repo add satapps https://satelliteapplicationscatapult.github.io/helm-charts
helm repo update
```

You can then list the available charts with:

```bash
helm search satapps
```
