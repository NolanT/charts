# Helm Charts

[Helm](https://helm.sh) repo for different charts which can be installed on [Kubernetes](https://kubernetes.io)

### Add Helm repository

To install the repo just run:

```bash
helm repo add nolant https://nolant.github.io/charts/
helm repo update
```

### Helm Charts

* [alarmserver](https://github.com/nolant/DSCAlarm)

  ```bash
  helm install alarmserver nolant/alarmserver
  ```
