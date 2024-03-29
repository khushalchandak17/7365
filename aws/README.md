# aws-usea1-qa-qa

![Version: 2.0.427](https://img.shields.io/badge/Version-2.0.427-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 2.0.427](https://img.shields.io/badge/AppVersion-2.0.427-informational?style=flat-square)

Fleet Workspace

**Homepage:** <https://fleet.rancher.io>

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| clustergroups | list | see [values](values.yaml) | Fleet [ClusterGroups](https://fleet.rancher.io/cluster-group) |
| commonAnnotations | object | `{}` | Add annotations to all the deployed resources |
| commonLabels | object | `{}` | Add labels to all the deployed resources |
| fullnameOverride | string | `nil` | String to fully override helper.fullname template |
| gitrepos | list | see [values](values.yaml) | Fleet [GitRepos](https://fleet.rancher.io/gitrepo-add) |
| nameOverride | string | `nil` | String to partially override helper.fullname template (will maintain the release name) |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.11.0](https://github.com/norwoodj/helm-docs/releases/v1.11.0)
