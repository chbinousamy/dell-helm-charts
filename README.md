## PROFINET
[![PROFINET CI](https://github.com/chbinousamy/_profinet/actions/workflows/build.yml/badge.svg)](https://github.com/chbinousamy/_profinet/actions/workflows/build.yml)


## Position GNSS-SDR
[![CI](https://github.com/chbinousamy/gnss-sdr/actions/workflows/main.yml/badge.svg)](https://github.com/chbinousamy/gnss-sdr/actions/workflows/main.yml)
[![CI](https://github.com/chbinousamy/gnss-sdr/actions/workflows/volk_gnsssdr_archs.yml/badge.svg)](https://github.com/chbinousamy/gnss-sdr/actions/workflows/volk_gnsssdr_archs.yml)
[![CI](https://github.com/chbinousamy/gnss-sdr/actions/workflows/gnss-sdr_archs.yml/badge.svg)](https://github.com/chbinousamy/gnss-sdr/actions/workflows/gnss-sdr_archs.yml)

## Linux-CAN / SocketCAN
can-utils

[![SocketCAN CodeQL Analysis](https://github.com/chbinousamy/can-utils/actions/workflows/codeql-analysis.yml/badge.svg)](https://github.com/chbinousamy/can-utils/actions/workflows/codeql-analysis.yml)
[![SocketCAN Build x86 arch](https://github.com/chbinousamy/can-utils/actions/workflows/build-x86.yml/badge.svg)](https://github.com/chbinousamy/can-utils/actions/workflows/build-x86.yml)
[![SocketCAN Build in riscv64](https://github.com/chbinousamy/can-utils/actions/workflows/build-riscv64.yml/badge.svg)](https://github.com/chbinousamy/can-utils/actions/workflows/build-riscv64.yml)
[![SocketCAN Build in armv7](https://github.com/chbinousamy/can-utils/actions/workflows/build-armv7.yml/badge.svg)](https://github.com/chbinousamy/can-utils/actions/workflows/build-armv7.yml)
[![SocketCAN Build in aarch64](https://github.com/chbinousamy/can-utils/actions/workflows/build-aarch64.yml/badge.svg)](https://github.com/chbinousamy/can-utils/actions/workflows/build-aarch64.yml)

can-tests
[![Build](https://github.com/chbinousamy/can-tests/actions/workflows/c-cpp.yml/badge.svg)](https://github.com/chbinousamy/actions/workflows/c-cpp.yml)


## Porcinet
[![Porcinet CI](https://github.com/chbinousamy/porcinet/actions/workflows/c-cpp.yml/badge.svg)](https://github.com/chbinousamy/porcinet/actions/workflows/c-cpp.yml)

## Python
[![Python Test](https://github.com/chbinousamy/cpython/actions/workflows/build.yml/badge.svg)](https://github.com/chbinousamy/cpython/actions/workflows/build.yml)


<!--
Copyright (c) 2021 Dell Inc., or its subsidiaries. All Rights Reserved.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0
-->

# Dell Community Kubernetes Helm Charts

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](docs/CODE_OF_CONDUCT.md)
[![License](https://img.shields.io/github/license/dell/helm-charts)](LICENSE)

The source for Dell Helm charts [Dell Helm Hub](https://github.com/dell/helm-charts).

For more information about installing and using Helm, see the
[Helm Docs](https://helm.sh/docs/). For a quick introduction to Charts, see the [Chart Guide](https://helm.sh/docs/topics/charts/).

## Where to Find Us

For all your support needs or to follow the latest ongoing discussions and updates, join our Slack group. Click [Here](http://del.ly/Slack_request) to request your invite.

You can also interact with us by creating a [GitHub issue](https://github.com/dell/helm-charts/issues).

## How to Install

```console
$ helm repo add dell https://dell.github.io/helm-charts
```

For documentation, please visit [Container Storage Modules documentation](https://dell.github.io/csm-docs/docs/observability/deployment/helm#configuration).

## Contributing to an Existing Chart

We'd love for you to contribute to an existing Chart that you find provides a useful application or service for Kubernetes. Please read our [Contribution Guide](docs/CONTRIBUTING.md) for more information on how you can contribute Charts.

## Owning and Maintaining A Chart

Individual charts can be maintained by one or more users of [OWNERS](OWNERS). When someone maintains a chart they have the access to merge changes to that chart. To have merge access to a chart someone needs to:

1. Be listed on the chart, in the [OWNERS](OWNERS) file, as a maintainer. If you need sponsors and have contributed to the chart, please reach out to the existing maintainers, or if you are having trouble connecting with them, please reach out to one of the [OWNERS](OWNERS) of the charts repository.

## Review Process

For information related to the review procedure used by the Chart repository maintainers, see [Merge approval and release process](docs/CONTRIBUTING.md).

## Versioning Strategy

Dell Helm Charts follow Semantic Versioning as defined on [http://semver.org/](http://semver.org).
