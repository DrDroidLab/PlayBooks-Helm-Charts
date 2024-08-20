# Helm Charts for GKE
This folder includes the helm charts compatible with Standard GKE Clusters in GCP.

## Pre-Requisite
[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

## Usage

Run the following:

```
helm install playbooks .
```

Find your service external IP to access the portal:
```
kubectl get svc web -o jsonpath='{.status.loadBalancer.ingress[0].ip}'
```

Note:
- Make sure you have setup the correct kubeconfig when running the helm install command.
- Add the namespace ```--namespace <namespace>``` at the end for installing in a specific namespace.
- Read the specific installation details mentioned in the README.md files in the respective folders.

## Contributing
We'd love to have you contribute! Please refer to our [contribution guidelines](https://docs.drdroid.io/docs/contributing) for details.