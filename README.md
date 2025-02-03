# Begonia Kernel Archiver
[![CI](https://github.com/cvnertnc/begonia_kernel_archiver/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/cvnertnc/begonia_kernel_archiver/actions/workflows/ci.yml)

This repository contains the kernel source code for the Xiaomi Redmi Note 8 Pro (Begonia) device. It is set up to automatically monitor kernel commits using GitHub Actions workflows and update the `update.md` file with the latest commit ID on a daily basis.

## Features

- **Automated Daily Checks:** A GitHub Actions workflow runs daily to scan for new commits.
- **Commit Tracking:** The workflow gathers commit data and records the latest commit ID in `update.md`.
- **Open Source Licensing:** This project is licensed under the GNU General Public License v3.0.

## Workflow Overview

The GitHub Actions workflow in this repository performs the following tasks:
1. **Commit Check:** Checks the repository for any new commits.
2. **Commit Retrieval:** Fetches the commit history.
3. **Latest Commit Extraction:** Extracts the latest commit ID.
4. **Update File:** Updates the `update.md` file with the newest commit ID.

## Usage

Simply push your changes to the repository. The scheduled workflow will automatically track commits and update the `update.md` file accordingly. No manual intervention is required.

## License

This project is licensed under the GNU General Public License v3.0. See the [LICENSE](LICENSE) file for more details.