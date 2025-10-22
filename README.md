# Semux Core

[![Build Status](https://api.travis-ci.com/semuxproject/semux-core.svg)](https://travis-ci.com/semuxproject/semux-core).
[![Build status](https://ci.appveyor.com/api/projects/status/dkeif4luqj7fymi7?svg=true)](https://ci.appveyor.com/project/semuxproject/semux-core)
[![Crowdin](https://badges.crowdin.net/semux-core/localized.svg)](https://crowdin.com/project/semux-core)

## What is Semux

Semux is an experimental high-performance blockchain platform that powers decentralized application. It's written purely in Java and powered by Semux BFT consensus algorithm.

More info can be found at our [Documentation page](./docs/README.md).


## Get started

1. Download the [Latest Release](https://github.com/semuxproject/semux-core/releases) and unpack it to a desired directory.
2. Run `semux-gui.bat` if you're on Windows, or `./semux-gui.sh` if you're on Linux or macOS.
3. *(Windows user) You may need to install [Microsoft Visual C++ 2012 Redistributable Package (x64)](https://www.microsoft.com/en-us/download/details.aspx?id=30679).*


## Build from source

Prerequisites:
```
OpenJDK 11
Apache Maven 3.5.2
```

Build:
```
git clone https://github.com/semuxproject/semux-core
cd semux
mvn install -DskipTests
```

Run:
```
./dist/linux/semux-cli.sh
```

## Contribute

Anyone is welcome to contribute to this open source project in the form of peer review, testing and patches. Please see the [contributing](./.github/CONTRIBUTING.md) guide for more details.

If you find a bug, please submit it to [issues](https://github.com/semuxproject/semux-core/issues).


## Wallet Localization

If you want to add new language, review/update existing translation or help to finish specific translations, you can join and do that by following link:
https://crowdin.com/project/semux-core


## License

[The MIT License](./LICENSE)
