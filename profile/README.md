# firv-comp

The organization `firv-comp` was created with the intention of holding the code created during the work on the "Language-based methods of control-flow integrity protection in RISC-V architectures" Master Thesis by Szymon Wróbel.

## Goals

The main goal of FIRV (**F**ault **I**njection in **R**ISC-**V**) project is presenting a general approach to modifying the compiler toolchain, allowing to include countermeasures protecting against certain attacks.

The primary focus, stemming from Szymon Wróbel's thesis, were countermeasures against Fault Injection attacks.

## Contributors
Szymon Wróbel ([@KatJon](https://github.com/KatJon))


## Contribution guidelines
Currently, the organization doesn't accept any external contributions or pull requests. For further information, please contact [@KatJon](https://github.com/KatJon).

## Project Contents

FIRV project consists of a number of repositories, with a few being forks of the upstream projects:

* [`firv-core`](https://github.com/firv-comp/firv-core) is a core repository of the project, containing example programs used for testing the built tools. It is also a home for the build commands, miscellanous configuration files and the root documentation of the project.
    + More information in [README.md](https://github.com/firv-comp/firv-core/blob/master/README.md)

* [`firv-rust`](https://github.com/firv-comp/firv-rust) is the fork of [`rust-lang/rust`](https://github.com/rust-lang/rust) containing the changes required for FIRV project.
    + More information in [firv/README.md](https://github.com/firv-comp/firv-rust/blob/develop/firv/README.md)

* [`firv-llvm-project`](https://github.com/firv-comp/firv-llvm-project) is the fork of [`llvm/llvm-project`](https://github.com/llvm/llvm-project). The repository contains the changes to LLVM project required for FIRV features.
    + More information in [firv-README.md](https://github.com/firv-comp/firv-llvm-project/blob/firv-main/firv-README.md)

* [`firv-rust-llvm-project`](https://github.com/firv-comp/firv-rust-llvm-project) is the fork of [`rust-lang/llvm-project`](https://github.com/rust-lang/llvm-project). The base repository is the rust-specific fork of LLVM project. This repository contains cherry-picked changes from [`firv-llvm-project`](https://github.com/firv-comp/firv-llvm-project).