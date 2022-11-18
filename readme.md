# helmfile-test

To run test with helmfiles pattern:

```sh
helmfile -e default -n helmfiles-test -f using-helmfiles/helmfile.yaml sync
```

To run test with releases pattern:

```sh
helmfile -e default -n releases-test -f using-releases/helmfile.yaml sync
```
