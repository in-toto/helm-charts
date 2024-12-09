# helm-charts

in-toto helm charts

This repository is the source code of https://in-toto.github.io/helm-charts

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Also, check Visit [https://in-toto.io](https://in-toto.io) to get started with
in-toto.

Once Helm has been set up correctly, add the repo as follows:

```bash
helm repo add in-toto  https://in-toto.github.io/helm-charts
```

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

#### Values

```bash
helm show values in-toto/archivista
```

### Installing

```bash
helm install archivista in-toto/archivista
```

See https://github.com/in-toto/helm-charts/tree/main/charts/archivista for more
information.
