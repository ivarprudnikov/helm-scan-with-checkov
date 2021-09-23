Scan helm chart with Checkov
================

[![CI Scanner](https://github.com/ivarprudnikov/helm-scan-with-checkov/actions/workflows/scanner.yml/badge.svg)](https://github.com/ivarprudnikov/helm-scan-with-checkov/actions/workflows/scanner.yml)

An example showing how to scan the Helm chart with the Checkov tool.

To see the output check the last build on https://github.com/ivarprudnikov/helm-scan-with-checkov/actions/workflows/scanner.yml

**Prerequisites**

* Docker

**Run locally**

`./test.sh`

## Heml chart

See `mychart/` dir that was generated with `helm create mychart`

## Checkov config

See `.checkov.yaml`

Docs https://www.checkov.io/1.Welcome/What%20is%20Checkov.html

