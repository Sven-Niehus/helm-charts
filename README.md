# [helm-charts](https://github.com/Sven-Niehus/helm-charts)

## Usage

[Helm](https://helm.sh) must be installed to use the charts. Please refer to Helm's [documentation](https://helm.sh/docs) to get started. Once Helm has been set up correctly, add the repo as follows:

```sh
helm repo add svenniehus https://charts.niehus.eu
```

If you had already added this repo earlier, run `helm repo update` to retrieve the latest versions of the packages. Use `helm search repo svenniehus` to see a list of all available charts.

You can install a chart release using the following command:

```sh
helm install <release> svenniehus/<chart> --values values.yaml
```

To uninstall a chart release use `helm`'s delete command:

```sh
helm delete <chart>
```

## Charts

| Chart                                                                                                     | Version  |     AppVersion      |
| --------------------------------------------------------------------------------------------------------- | :------: | :-----------------: |
| [`cloudflared`](https://github.com/Sven-Niehus/helm-charts/tree/main/charts/snapdrop)                     | `1.0.0`  |   `c8c728ba-ls37`   |