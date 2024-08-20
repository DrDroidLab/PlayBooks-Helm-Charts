# Doctor Droid Playbooks Kubernetes Helm Charts
This repository hosts helm charts compatible with kubernetes engine from different cloud providers.

## Pre-Requisite
[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

## Usage
Once Helm is set up properly, go inside the folder of the kuberentes engine you are trying to deploy with and follow the instructions in the README file.

Note:
- Make sure you have setup the correct kubeconfig when running the helm install command.
- Add the namespace ```--namespace <namespace>``` at the end for installing in a specific namespace.

## Contributing
We'd love to have you contribute! Please refer to our [contribution guidelines](https://docs.drdroid.io/docs/contributing) for details.