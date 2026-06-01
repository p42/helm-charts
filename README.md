# Project42 Helm Charts

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Official [Helm](https://helm.sh) chart repository for **Project42 (P42)**.

## Overview

This repository contains Helm charts for deploying and managing Project42 services and applications on Kubernetes.

## Usage

### Add the Helm Repository

```bash
helm repo add p42 https://p42.github.io/helm-charts
helm repo update
```

### Install a Chart

```bash
helm install <release-name> p42/<chart-name>
```

### Search Available Charts

```bash
helm search repo p42
```

## Charts

| Chart | Description | Version |
|-------|-------------|---------|
| *(coming soon)* | | |

## Contributing

1. Fork this repository
2. Create a feature branch (`git checkout -b feature/my-chart`)
3. Add or update charts following the [Helm chart best practices](https://helm.sh/docs/chart_best_practices/)
4. Commit your changes and open a pull request

## License

This project is licensed under the [MIT License](LICENSE).
