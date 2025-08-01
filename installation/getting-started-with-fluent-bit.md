---
description: A guide on how to install, deploy, and upgrade Fluent Bit
---
# Get started with Fluent Bit

<img referrerpolicy="no-referrer-when-downgrade" src="https://static.scarf.sh/a.png?x-pxid=e9732f9c-44a4-46d3-ab87-86138455c698" />

## Container deployment

| Deployment Type   | Instructions |
| ----------------- | -------------------------------------------------- |
| Kubernetes        | [Deploy on Kubernetes](kubernetes.md#installation) |
| Docker            | [Deploy with Docker](docker.md)                    |
| Containers on AWS | [Deploy on Containers on AWS](aws-container.md)    |

## Install on Linux (packages)

| Operating System       | Installation instructions |
| ---------------------- | ------------------------- |
| CentOS / Red Hat       | [CentOS 7](linux/redhat-centos.md#install-on-redhat-centos), [CentOS 8](linux/redhat-centos.md#install-on-redhat-centos), [CentOS 9 Stream](linux/redhat-centos.md#install-on-redhat-centos) |
| Ubuntu                 | [Ubuntu 16.04 LTS](linux/ubuntu.md), [Ubuntu 18.04 LTS](linux/ubuntu.md), [Ubuntu 20.04 LTS](linux/ubuntu.md), [Ubuntu 22.04 LTS](linux/ubuntu.md) |
| Debian                 | [Debian 10](linux/debian.md), [Debian 11](linux/debian.md), [Debian 12](linux/debian.md) |
| Amazon Linux           | [Amazon Linux 2](linux/amazon-linux.md#install-on-amazon-linux-2), [Amazon Linux 2022](linux/amazon-linux.md#amazon-linux-2022) |
| Raspbian / Raspberry Pi | [Raspbian 10](linux/raspbian-raspberry-pi.md#raspbian-10-buster), [Raspbian 11](linux/raspbian-raspberry-pi.md#raspbian-11-bullseye) |
| Yocto / Embedded Linux | [Yocto / Embedded Linux](yocto-embedded-linux.md#fluent-bit-and-other-architectures) |
| Buildroot / Embedded Linux | [Buildroot / Embedded Linux](buildroot-embedded-linux.md) |

## Install on Windows (packages)

| Operating System    | Installation instructions |
| ------------------- | ------------------------- |
| Windows Server 2019 | [Windows Server `EXE`](windows.md#installing-from-exe-installer), [Windows Server ZIP](windows.md#installing-from-zip-archive) |
| Windows 10 2019.03  | [Windows `EXE`](windows.md#installing-from-exe-installer), [Windows ZIP](windows.md#installing-from-zip-archive)               |

## Install on macOS (packages)

| Operating System    | Installation instructions                     |
| ------------------- | --------------------------------------------- |
| macOS               | [Homebrew](macos.md#installing-from-homebrew) |

## Compile from source (Linux, Windows, FreeBSD, macOS)

| Operating system | Installation instructions                                   |
| ---------------- | ----------------------------------------------------------- |
| Linux, FreeBSD   | [Compile from source](sources/build-and-install.md)         |
| macOS            | [Compile from source](macos.md#compile-from-source) |
| Windows          | [Compile from Source](windows.md#compile-from-source)       |

## Sandbox environment

If you are interested in learning about Fluent Bit you can try out the sandbox environment:

{% embed url="https://play.instruqt.com/embed/Fluent/tracks/fluent-bit-getting-started-101?token=em_S2zOzhhDQepM0vDS" %}
Fluent Bit sandbox environment
{% endembed %}

## Enterprise packages

Fluent Bit packages are also provided by [enterprise providers](https://fluentbit.io/enterprise) for older end of life versions, Unix systems, and additional support and features including aspects like CVE backporting.
