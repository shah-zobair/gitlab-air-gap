[![pipeline status](https://gitlab.com/gitlab-org/charts/gitlab/badges/master/pipeline.svg)](https://gitlab.com/gitlab-org/charts/gitlab/pipelines)

# Cloud Native GitLab Helm Chart

The `gitlab` chart is the best way to operate GitLab on Kubernetes. It contains
all the required components to get started, and can scale to large deployments.

Some of the key benefits of this chart and [corresponding containers](https://gitlab.com/gitlab-org/build/CNG) are:

- Improved scalability and reliability.
- No requirement for root privileges.
- Utilization of object storage instead of NFS for storage.

## Detailed documentation

See the [repository documentation](doc/index.md) for how to install GitLab and
other information on charts, tools, and advanced configuration.

For easy of reading, you can find this documentation rendered on
[docs.gitlab.com/charts](https://docs.gitlab.com/charts).

### Configuration Properties

We're often asked to put a table of all possible properties directly into this README.
These charts are _massive_ in scale, and as such the number of properties exceeds
the amount of context we're comfortable placing here. Please see our (nearly)
[comprehensive list of properties and defaults](doc/installation/command-line-options.md).

**Note:** We _strongly recommend_ following our complete documentation, as opposed to
jumping directly into the settings list.

## Architecture and goals

See [architecture documentation](doc/architecture/index.md) for an overview
of this project goals and architecture.

## Known issues and limitations

See [limitations](doc/index.md#limitations).

## Release Notes

Check the [releases documentation](doc/releases/index.md) for information on important releases,
and see the [changelog](CHANGELOG.md) for the full details on any release.

## Contributing

See the [contribution guidelines](CONTRIBUTING.md) and then check out the
[development styleguide](doc/development/index.md).



List of source Images:


registry.gitlab.com/gitlab-org/cloud-native/gitlab-operator:0.8.1 quay.io/szobair/gitlab-operator:0.8.1
registry.gitlab.com/gitlab-org/build/cng/gitaly:v15.2.2 quay.io/szobair/gitaly:v15.2.2
registry.gitlab.com/gitlab-org/build/cng/kubectl:1.18.20 quay.io/szobair/kubectl:1.18.20
registry.gitlab.com/gitlab-org/cloud-native/mirror/images/busybox:latest quay.io/szobair/busybox:latest
registry.gitlab.com/gitlab-org/build/cng/cfssl-self-sign:1.6.1 quay.io/szobair/cfssl-self-sign:1.6.1
docker.io/bitnami/postgresql:12.7.0 quay.io/szobair/postgresql:12.7.0
docker.io/bitnami/redis:6.0.9-debian-10-r0 quay.io/szobair/redis:6.0.9-debian-10-r0
docker.io/bitnami/redis-exporter:1.12.1-debian-10-r11 quay.io/szobair/redis-exporter:1.12.1-debian-10-r11
docker.io/bitnami/postgres-exporter:0.8.0-debian-10-r99 quay.io/szobair/postgres-exporter:0.8.0-debian-10-r99
gcr.io/kubebuilder/kube-rbac-proxy:1.18.20 quay.io/szobair/kube-rbac-proxy:1.18.20
registry.gitlab.com/gitlab-org/cloud-native/mirror/images/defaultbackend-amd64:1.5 quay.io/szobair/defaultbackend-amd64:1.5
docker.io/minio/minio:RELEASE.2017-12-28T01-21-00Z quay.io/szobair/minio:RELEASE.2017-12-28T01-21-00Z
registry.gitlab.com/gitlab-org/build/cng/alpine-certificates20191127-r2@sha256:367d437d024d7647432d67fb2442e3e5723af5930bad77d3535f4f8f4f8630d9
docker.io/bitnami/redis-exporter:1.12.1-debian-10-r11
docker.io/bitnami/postgres-exporter:0.8.0-debian-10-r99
registry.gitlab.com/gitlab-org/build/cng/gitlab-toolbox-ee:v15.4.1
registry.gitlab.com/gitlab-org/build/cng/gitlab-webservice-ee:v15.4.1
registry.gitlab.com/gitlab-org/build/cng/gitlab-workhorse-ee:v15.4.1
registry.gitlab.com/gitlab-org/build/cng/gitlab-container-registry:v3.57.0-gitlab
registry.gitlab.com/gitlab-org/build/cng/gitlab-exporter:11.18.2
registry.gitlab.com/gitlab-org/build/cng/gitlab-kas:master
registry.gitlab.com/gitlab-org/build/cng/gitlab-webservice-ee:v15.4.1
registry.gitlab.com/gitlab-org/cloud-native/mirror/images/busybox:latest
registry.gitlab.com/gitlab-org/gitlab-runner:alpine-v15.4.0
quay.io/jetstack/cert-manager-cainjector:v1.5.4
quay.io/jetstack/cert-manager-controller:v1.5.4
quay.io/jetstack/cert-manager-webhook:v1.5.4
