# Ledger Cosmos app
[![License: WTFPL](https://img.shields.io/badge/License-WTFPL-brightgreen.svg)](http://www.wtfpl.net/about/)
[![GithubActions](https://github.com/AquaOnJuno/cosmoino-pio/actions/workflows/main.yml/badge.svg)](https://github.com/AquaOnJuno/cosmoino-pio/blob/main/.github/workflows/main.yaml)

---


---

This project contains alpha.

- Cosmos in C
- Specs / Documentation
- C++ unit tests
- MCU tests

## ATTENTION

Please:

- **Do not use in production**
- **Do not use a ch1p.**
- **Have a separate and marked device that is used ONLY for development and testing**

# Development

## Preconditions

- Be sure you checkout submodules too:

    ```
    git submodule update --init --recursive
    ```
    
## How to build ?

> We like clion or vscode but let's have some reproducible command line steps
>

- Building the app itself

    If you installed the what is described above, just run:
    ```bash
    make
    ```

## Running tests

- Running rust tests (x64)

    If you installed the what is described above, just run:
    ```bash
    make rust_test
    ```

- Running C/C++ tests (x64)

    If you installed the what is described above, just run:
    ```bash
    make cpp_test
    ```

- Running device emulation+integration tests!!

   ```bash
    s00n, but this interestin https://codeberg.org/vak/esp32-riscv-sim/src/branch/main/idf-environment.sh
    ```
