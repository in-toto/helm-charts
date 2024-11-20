# helm-charts

in-toto helm charts


## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Also, check Visit [https://in-toto.io](https://in-toto.io) to get started with
in-toto.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add in-toto https://in-toto.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
in-toto` to see the charts.

## Charts

You can search all in-toto charts using following command:

```bash
helm search repo in-toto
```


### Archivista

This is a helm chart to deploy the Archivista.

See http://github.com/in-toto/helm-charts/charts/archivista for more information.
