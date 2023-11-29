# gh istio-envoy-version

This [`gh` CLI extension](https://cli.github.com/manual/gh_extension) resolves the envoy version of an Istio release or any commit SHA.

## Install

```
gh extension install dio/gh-istio-envoy-version
```

## Usage

To get the latest Envoy proxy version information of Istio master branch.

```
gh istio-envoy-version
```

For a specific ref:

```
gh istio-envoy-version 1.20.0
gh istio-envoy-version 2a7f00169241757f1fcea803df26d7e61148717d
```
