# Personal Charts

## Update a Chart
```sh
podman run --rm --volume "$(pwd)/charts/k3s-sqlite-to-s3:/helm-docs" -u $(id -u) docker.io/jnorwood/helm-docs:latest
```