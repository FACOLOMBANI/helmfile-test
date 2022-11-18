# helmfile-test

## To run test with helmfiles pattern:

```sh
helmfile -e default -n helmfiles-test -f using-helmfiles/helmfile.yaml sync
```

The results will be a sequential order of deployment, each waiting to be ready to deploy next one.

## To run test with releases pattern:

```sh
helmfile -e default -n releases-test -f using-releases/helmfile.yaml sync
```

The results will be a concurrent deployment.
