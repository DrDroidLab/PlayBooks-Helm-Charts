# Helm Charts for EKS
This folder includes the helm charts compatible with EKS from AWS.

## Pre-Requisite
[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

## Usage

You will need to mention the subnets of your kubernetes cluster in the ```web-ingress.yaml``` file.

Once subnets are added, run the following:

```console
helm install playbooks .
```
Note:
- Make sure you have setup the correct kubeconfig when running the helm install command.
- Add the namespace ```--namespace <namespace>``` at the end for installing in a specific namespace.
- Read the specific installation details mentioned in the README.md files in the respective folders.

## Contributing
We'd love to have you contribute! Please refer to our [contribution guidelines](https://docs.drdroid.io/docs/contributing) for details.