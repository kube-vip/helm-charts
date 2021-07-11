# helm-charts
Helm charts for kube-vip

```bash
$ helm repo add kube-vip https://kube-vip.io/helm-charts/
$ helm repo update
```

## Prerequisites

- Helm 3.x

## Adding this helm repository

To add this repository to the helm configuration:

```bash
$ helm repo add kube-vip https://kube-vip.io/helm-charts/
```

## Using this helm repository

To install a chart from this repository (example with Redis):

```bash
$ helm install kube-vip kube-vip.io/helm-charts/kube-vip
```

## Removing this helm repository

To remove the helm repository from helm configuration:

```bash
$ helm repo remove kube-vip
```

