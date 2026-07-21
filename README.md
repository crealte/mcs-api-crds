# mcs-api-crds

This repository publishes [MCS API](https://github.com/kubernetes-sigs/mcs-api) CRDs as Helm charts.

## Usage

### Versioning

The 'v' prefix from upstream releases is removed so for example `v0.5.0` is packaged `0.5.0`.

### Install
```bash
helm install mcs-api-crds oci://ghcr.io/crealte/charts/mcs-api-crds
```

### Uninstall
```bash
helm uninstall mcs-api-crds
```