# V8-Ignition-Analyzer

## Overview
This project automates the setup and initial exploration of the V8 JavaScript engine’s Ignition interpreter using GitHub Actions. It installs V8, symbolic execution tools (Angr, KLEE, QSYM), and verifies a successful build.

## Features
- Automated setup of **V8 JavaScript Engine**
- Installation of **symbolic execution tools** (Angr, KLEE, QSYM)
- Verification of the **Ignition interpreter build**
- Lists key **Ignition source files** for further analysis

## Setup Instructions

To manually set up this project, follow these steps:

### 1️⃣ Install Dependencies
```bash
sudo apt update && sudo apt install -y python3-pip clang lld llvm cmake ninja-build
