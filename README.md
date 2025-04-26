# Begonia Kernel Archiver
[![CI](https://github.com/cvnertnc/begonia_kernel_archiver/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/cvnertnc/begonia_kernel_archiver/actions/workflows/ci.yml)

This repository contains the kernel source code for the Xiaomi Redmi Note 8 Pro (Begonia) device. It is set up to automatically monitor kernel commits using GitHub Actions workflows and keep the branches up-to-date with their respective upstream sources.

## Features

- **Automated Daily Sync:** GitHub Actions workflows run daily to sync the branches (`astera`, `nova`, `power`) with their upstream repositories.
- **Upstream Tracking:** Each branch is kept in sync with its corresponding upstream source, ensuring the latest commits are always available.
- **Open Source Licensing:** This project is licensed under the GNU General Public License v3.0.

## Workflow Overview

The GitHub Actions workflows in this repository perform the following tasks:
1. **Upstream Sync:** Fetches the latest commits from the upstream repositories.
2. **Branch Update:** Updates the local branches (`astera`, `nova`, `power`) with the latest upstream changes.
3. **Force Push:** Pushes the updated branches to this repository.

## Usage

Simply push your changes to the repository. The scheduled workflows will automatically sync the branches with their upstream sources. No manual intervention is required.

## Kernels

Astera Kernel By [MrErenK](https://github.com/xiaomi-begonia-dev/android_kernel_xiaomi_mt6785)

Power Kernel By [Saikrishna1504](https://github.com/Saikrishna1504/kernel_xiaomi_mt6785)

Nova Kernel By [Wahid7852](https://github.com/Wahid7852)

## License

This project is licensed under the GNU General Public License v3.0. See the [LICENSE](LICENSE) file for more details.
