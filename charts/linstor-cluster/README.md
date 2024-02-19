# LinstorCluster and LinstorSattelitConfig

Deploy the LinstorCluster and LinstorSattelitConfig via helm chart

## Usage

First, ensure you have Piraeus Operator installed

Then install this chart:

```
helm repo add dtrdnk-helm-charts https://dtrdnk.github.io/helm-charts
helm install linstor-cluster dtrdnk-helm-charts/linstor-cluster
```

Check out the available options:

```
helm show values piraeus-charts/linstor-cluster
```
