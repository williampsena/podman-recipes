# About

This repository contains Podman examples such as network, volumes, environment variables, and other features.

# How do you play the podman yaml files?

Always build the podman yaml file from the root directory, for example:

```shell
podman play kube pods/whoami.yaml
```

# How do you generate kubernetes pod yaml file?

```shell
# stdout
podman generate kube whoami

# write ile
podman generate kube whoami > /tmp/pod.yaml
```

# How do you tear down pods?

```shell
podman play kube --down pods/whoami.yaml
```

# Related articles

- [Running the Traefik, my favorite Edge Router with Podman](https://willsena.dev/running-the-traefik-my-favorite-cloud-edge-router-with-podman/)
 - [How to Run Secure Pods with Podman](https://willsena.dev/how-to-run-secure-pods-with-podman/)
 - [Building Kubernetes-style pods with Podman](https://willsena.dev/building-kubernetes-style-pods-with-podman/)