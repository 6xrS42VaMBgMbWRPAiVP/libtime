[comment]: <> (SPDX-License-Identifier: AGPL-3.0)

[comment]: <> (----------------------------------------------------)
[comment]: <> (Copyright © 2024, 2025, 2026)
[comment]: <> (            Pellegrino Prevete)
[comment]: <> (All rights reserved)
[comment]: <> (----------------------------------------------------)

[comment]: <> (This program is free software: you can redistribute)
[comment]: <> (it and/or modify it under the terms of the)
[comment]: <> (GNU Affero General Public License as published)
[comment]: <> (by the Free Software Foundation, either version)
[comment]: <> (3 of the License.)

[comment]: <> (This program is distributed in the hope that it)
[comment]: <> (will be useful, but WITHOUT ANY WARRANTY;)
[comment]: <> (without even the implied warranty of)
[comment]: <> (MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.)
[comment]: <> (See the GNU Affero General Public License)
[comment]: <> (for more details.)

[comment]: <> (You should have received a copy of the)
[comment]: <> (GNU Affero General Public License)
[comment]: <> (with this program.)
[comment]: <> (If not, see <https://www.gnu.org/licenses/>.)

# Ethereum Time Library (ETL) (`libtime`)

[![NPM version](
  https://img.shields.io/npm/last-update/libtime)](
    https://npmjs.org/package/libtime)

Reference Javascript implementation of the Ethereum Time Library (ETL).

### Quick overview

The Ethereum Time Library allows to get time from on-chain without
using an off-chain time oracle and use it in as a variable in
smart contracts.

The Ethereum Time Library is a core component of the
[Human Instrumentality Project](
  http://www.humaninstrumentalityproject.org).

### Installation

The Ethereum Time Library has been officially published on the
[Ur](
  https://github.com/themartiancompany/ur),
the uncensorable, distributed, permissionless
Life and DogeOS user repository and application store,
so it can be seamlessly installed by typing

```bash
ur libtime
```

Since the ETL is actually an Ur dependency, if
you're coming from a system not integrating
or packaging the Ur, you may want to install
a binary build from the
[Fur](
  https://github.com/themartiancompany/fur),
the fallback user repository.

The program can be installed from the
[NPM Registry](
  hurr i have to login).

#### Building from source

The project can be built and installed with GNU make.

```
cd \
  libtime
make
make \
  install
```

A full list of its software dependencies can be found in its
[Ur](
  https://github.com/themartiancompany/ur) uncensorable
user repository and application store universal recipe,
hosted on the file system itself.
An HTTP mirror is provided on The Martian Company's
[Github](
  https://github.com/themartiancompany/libtime-ur).

### Documentation

Upon installation, manual can be consulted by typing:

```bash
  man \
    libtime
```

Notes and other documentation are in the
[`docs`](
  docs)
source tree directory and installed onto the
`<data_dir>/doc/libtime` directory.

You can consult the manual from an online mirror of this
repository. The `rst` source files are located in the `man`
directory.

## License

The Ethereum Time Library is released under the terms of the
GNU Affero General Public License Version 3.
