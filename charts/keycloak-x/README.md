# Keycloak

This chart bootstraps a [Keycloak.X](https://www.keycloak.org) deployment on a [Kubernetes](http://kubernetes.io) cluster using the [Helm](https://helm.sh) package manager.

[Keycloak](https://www.keycloak.org) is a high performance Java-based identity and access management solution. It lets developers add an authentication layer to their applications with minimum effort.

## Prerequisites

- Kubernetes 1.19+
- Helm 3.1+

## Installing the Chart

To install the chart with the release name `my-release`:

```bash
helm repo add awoimbee https://awoimbee.github.io/helm-charts
helm install my-release awoimbee/keycloak-x
```

## Notes

- Keycloak.X container: https://github.com/keycloak/keycloak-containers/tree/master/server-x
- Keycloak.X release: https://www.keycloak.org/2020/12/first-keycloak-x-release.adoc
