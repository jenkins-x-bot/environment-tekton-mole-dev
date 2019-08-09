# jxui-backup

|App Metadata||
|---|---|
| **Version** | 0.0.4 |
| **Description** | UI for the CloudBees Jxui V3 product |
| **Chart Repository** | http://chart.infra.jrawlings.co.uk |

## App README.MD

# UI for the CloudBees Jxui v3 product

This helm chart includes both the UI and jxui API server.

## Install

Install via Helm. Ensure you have the Jenkins X Helm repo added:

### Prerequisite

```
helm init
helm repo add chartmuseum http://chartmuseum.jenkins-x.io
```

or to update your helm repos

```
helm repo update
```

