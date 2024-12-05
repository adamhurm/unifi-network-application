# unifi-network-application

![Version: 0.1.1](https://img.shields.io/badge/Version-0.1.1-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 8.1.127-ls42](https://img.shields.io/badge/AppVersion-8.1.127--ls42-informational?style=flat-square)

A Helm chart for Kubernetes

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| Balazs Petrikovics | <bpetrikovics@gmail.com> |  |

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| fullnameOverride | string | `""` |  |
| image.pullPolicy | string | `"IfNotPresent"` |  |
| image.repository | string | `"linuxserver/unifi-network-application"` |  |
| image.tag | string | `""` |  |
| ingress.annotations | object | `{}` |  |
| ingress.hostname | string | `"unifi.local"` |  |
| ingress.ingressClassName | string | `nil` |  |
| ingress.redirect.annotations | object | `{}` |  |
| ingress.redirect.enabled | bool | `true` |  |
| ingress.tls | list | `[]` |  |
| mongodb.adminpassword | string | `""` |  |
| mongodb.adminSecret | string | `nil` | Overrides `mongodb.adminuser`, `mongodb.adminpassword` |
| mongodb.adminuser | string | `""` |  |
| mongodb.cacheSizeGB | string | `"0.25"` |  |
| mongodb.dbname | string | `"unifi"` |  |
| mongodb.dbname_stat | string | `"unifi_stat"` |  |
| mongodb.image | string | `"mongo"` |  |
| mongodb.imageTag | string | `"3.6"` |  |
| mongodb.password | string | `""` |  |
| mongodb.username | string | `""` |  |
| mongodb.userSecret | string | `nil` | Overrides `mongodb.username`, `mongodb.password` |
| mongodb.volumeMounts | list | `[]` |  |
| mongodb.volumes | list | `[]` |  |
| nameOverride | string | `""` |  |
| replicaCount | int | `1` |  |
| resources | object | `{}` |  |
| service.annotations | object | `{}` |  |
| service.loadBalancerIp | string | `nil` |  |
| service.type | string | `nil` |  |
| volumeMounts | list | `[]` |  |
| volumes | list | `[]` |  |

