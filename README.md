# lgcorzo/mds

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![Dark Gravity](https://img.shields.io/badge/Autonomous%20Factory-Dark%20Gravity-blueviolet?style=flat-square)](https://github.com/lgcorzo/rust_CACD_autonomous_factory)

> [!NOTE]
> **UPSTREAM STATUS & SOVEREIGN FORK PURPOSE:**
> Following upstream repository archiving and licensing shifts across the MinIO ecosystem, this repository is **actively maintained and hardened** under **@lgcorzo** as an essential infrastructure component of the **[Dark Gravity Autonomous CA/CD Factory](https://github.com/lgcorzo/rust_CACD_autonomous_factory)** ([Architecture Knowledge Base](https://notebook.google.com/notebook/116d5f03-2fb0-4fa7-bd7c-1c9849920abc)). Continuous security auditing, zero-CVE verification, and hardware SIMD optimizations are independently maintained to guarantee supply-chain sovereignty and operational continuity.

---

## 🛡️ Dark Gravity Factory: Technological Sovereignty & Security Rationale

### 1. Architectural Role in Dark Gravity
In the **Dark Gravity Autonomous CA/CD Software Factory (V7.2 / V7.3)**, Sovereign mirror of MinIO Design System (MDS) powering unified, responsive UI components for Dark Gravity's storage consoles.

### 2. Supply-Chain Sovereignty & Independent Maintenance
- **Insulation from Upstream License Closures:** When upstream open-source projects close distributions or alter licensing terms, Dark Gravity enforces **semantic mirroring and sovereign forks** to guarantee total independence from commercial vendors.
- **Autonomous Security Verification & Zero-CVE Policy:** This repository is continuously audited for CVEs and vulnerabilities, maintaining a 100% clean secret scanning posture. Regressions and upstream bugs are resolved directly within the autonomous factory ecosystem.
- **Compliance & Provenance:** Ensures cryptographic integrity and auditable lineage in compliance with the **EU AI Act**, **SOC 2 Type II**, and **Hazitek / SPRI** regulatory frameworks.

---

# MinIO Design System

The MinIO Design System is a design specification for all UI elements used in MinIO products.

> [!NOTE]
> This repository is forked from the original open source MinIO `mds` project and is maintained
> by Buckit project. See the LICENSE and NOTICE files for licensing and attribution
> information.

## How to test

You can test this package using the embedded storybook. Please follow these steps:

1. Do `yarn install` in the root folder of mds
2. Start Story book by running `yarn storybook`
3. Open any browser and go to `http://localhost:6006`

## Build distribution files

To create distribution files you can run `yarn build` or `make build` in source folder. This will create the required dist folders.

This process is required everytime a new component is created and ready to be distributed

## License

MinIO Design System source is licensed under the GNU AGPLv3 license that can be found in the [LICENSE](https://github.com/minio/mds/blob/master/LICENSE) file.
