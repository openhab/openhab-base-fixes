# Base Fixes

[![GitHub Actions Build Status](https://github.com/wborn/openhab-base-fixes/actions/workflows/ci-build.yml/badge.svg?branch=main)](https://github.com/wborn/openhab-base-fixes/actions/workflows/ci-build.yml)
[![GPLv2+CE](https://img.shields.io/badge/license-GPL%20v2%2BCE-green.svg)](https://openjdk.org/legal/gplv2+ce.html)

This bundle contains classes to workaround issues in the OpenJDK 17 implementation of the java.base module.

It contains the OpenJDK 11 implementation of the `LinkedTransferQueue` which can be used to workaround [JDK-8301341](https://bugs.openjdk.org/browse/JDK-8301341).
