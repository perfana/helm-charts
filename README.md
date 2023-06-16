# Perfana helm charts

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
helm repo add perfana https://perfana.github.io/helm-charts
```

You can then run `helm search repo perfana` to see the charts.

# Available charts 

## perfana

Setup a Perfana environment.

## perfana-secure-gateway

Setup a client side Perfana gateway to connect to Perfana Cloud via mTLS.

## perfana-fixture

Create a Perfana initial setup with a data fixture.