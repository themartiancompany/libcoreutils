[comment]: <> (SPDX-License-Identifier: AGPL-3.0)

[comment]: <> (-------------------------------------------------------------)
[comment]: <> (Copyright © 2024, 2025)
[comment]: <> (            Pellegrino Prevete)
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

[comment]: <> (You should have received a copy of the GNU Affero General)
[comment]: <> (Public License along with this program.)
[comment]: <> (If not, see <https://www.gnu.org/licenses/>.)


# Coreutils library (`libcoreutils.js`)

[![NPM version](
  https://img.shields.io/npm/last-update/tmcsplit)](
    https://npmjs.org/package/tmcsplit)

Javascript of some
[GNU Coreutils](
  https://www.gnu.org/software/coreutils)
programs.

Includes `base64`.

The Coreutils library is part of
[`senzacoreutils`](
  https://github.com/themartiancompany/senzacoreutils).

It uses the
[Encoding Tools](
  https://github.com/themartiancompany/encoding-tools)
and the 
[Crash Javacript](
  https://github.com/themartiancompany/crash-js)
library modules.

### Installation

You can install and save an entry to your `package.json`
with the following command:

```bash
npm \
  install \
    --save \
    "libcoreutils"
```

You can then run one of the programs with

```bash
npx \
  "base64"
```

or just with `base64.js` if you have installed
the program system-wide using npm from this source
repository or from the
[NPM Registry](
  https://www.npmjs.com/package/libcoreutils)

```
npm \
  -g \
  install \
    "libcoreutils"
```

or if using GNU make in this repository

```bash
make \
  install
```

**Note:** You may need admin rights (`sudo`,
`su -c` or on Windows `Run as administrator`).

or if you install it as a
[DogeOS](
  https://github.com/themartiancompany/dogeos)
package from the
[Ur](
  https://github.com/themartiancompany/ur)

```bash
ur \
  "nodejs-libcoreutils"
```

### Documentation

Upon installation the manual can be accessed with
`man base64.js` but really it's the same as
GNU Split, so you can also refer to `man base64`
for what is it implemented.

# License

This software by Pellegrino Prevete is released
under the terms of the GNU Affero General Public License
version 3.
