[comment]: <> (SPDX-License-Identifier: AGPL-3.0)

[comment]: <> (-------------------------------------------------------------)
[comment]: <> (Copyright © 2024, 2025  Pellegrino Prevete)
[comment]: <> (All rights reserved)
[comment]: <> (-------------------------------------------------------------)

[comment]: <> (This program is free software: you can redistribute)
[comment]: <> (it and/or modify it under the terms of the GNU Affero)
[comment]: <> (General Public License as published by the Free)
[comment]: <> (Software Foundation, either version 3 of the License.)

[comment]: <> (This program is distributed in the hope that it will be useful,)
[comment]: <> (but WITHOUT ANY WARRANTY; without even the implied warranty of)
[comment]: <> (MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the)
[comment]: <> (GNU Affero General Public License for more details.)

[comment]: <> (You should have received a copy of the GNU Affero General Public)
[comment]: <> (License along with this program.)
[comment]: <> (If not, see <https://www.gnu.org/licenses/>.)

# Github Ur (Gur)

A command-line utility to easily manage
[Ur](
  https://github.com/themartiancompany/ur)
repositories censorable Github HTTP mirrors.

The program depends on the
[Crash Bash](
  https://github.com/themartiancompany/crash-bash)
library,
the
[GitHub command-line utility](
  https://github.com/cli/cli)
and the
[PyGitHub](
  https://github.com/PyGithub/PyGithub)
Python library.

## Installation

The program in this source repo
can be installed from source using GNU Make.

```bash
make \
  install
```

The Gur has been officially published on the
the uncensorable
[Ur](
  https://github.com/themartiancompany/ur)
user repository and application store as
`gur`.
The source code is published on the
[Ethereum Virtual Machine File System](
  https://github.com/themartiancompany/evmfs)
so it can't possibly be taken down.

To install it from there just type

```bash
ur \
  gur
```

A censorable HTTP Github mirror of the recipe published there,
containing a full list of the software dependencies needed to run the
tools is hosted on
[gur-ur](
  https://github.com/themartiancompany/gur-ur).

Be aware the mirror could go offline any time as Github and more
in general all HTTP resources are inherently unstable and censorable.

## Documentation

For a quick manual you can type

```bash
man \
  "gur"
```

while a more complete documentation is
in the `docs` directory.

## License

This program is released by Pellegrino Prevete under the terms
of the GNU Affero General Public License version 3.
