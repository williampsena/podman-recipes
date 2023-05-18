# About

This repository contains Podman examples such as network, volumes, environment variables, and other features.

# How do you play the podman yaml files?

Always build the podman yaml file from the root directory, for example:

```shell
podman play kube pods/whoami.yaml
```

# How do you tear down pods?

```shell
podman play kube --down pods/whoami.yaml
```

# Related articles

 - [How to Run Secure Pods with Podman](https://willsena.dev/how-to-run-secure-pods-with-podman/)