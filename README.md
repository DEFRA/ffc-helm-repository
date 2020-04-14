# FFC Helm Library Chart Repository

A Helm chart public repository that contains FFC helm library charts. It can be used by any FFC microservice Helm chart which can then import K8s object templates configured to run on the FFC platform.

## Including the library chart

Steps:
  * Update `Chart.yaml` to `apiVersion: v2`
  * Add library chart under `dependencies`. Choose the version you want. Version number can include `~` or `^` to pick up latest PATCH and MINOR versions respectively


For information on how to use each template please check the [ffc-helm-library repo README](https://github.com/DEFRA/ffc-helm-library/blob/master/README.md)