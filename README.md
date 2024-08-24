## Usage

[Helm](http://helm.kubernetes.ac.cn) must be installed to use the charts.  Please refer to
Helm's [documentation](http://helm.kubernetes.ac.cn/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add msqtt https://msqtt.github.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
msqtt` to see the charts.

To install the moj chart:

    helm install my-<chart-name> msqtt/<chart-name>


To uninstall the chart:

    helm delete my-<chart-name>
