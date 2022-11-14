# KubeRay Helm Charts

This repository hosts Helm charts for the [KubeRay](https://github.com/ray-project/kuberay) project since KubeRay v0.4.0.

# Usage
[Helm](https://helm.sh/) must be installed to use the charts. Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```sh
helm repo add kuberay https://ray-project.github.io/kuberay-helm/
helm install kuberay kuberay/kuberay-operator
```

You can then run `helm search repo kuberay` to see the charts.