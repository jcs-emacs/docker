[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Linux](https://img.shields.io/badge/-Linux-fcc624?logo=linux&style=flat&logoColor=black)](#)
[![Docker Pulls](https://img.shields.io/docker/pulls/jcs090218/jcs-emacs.svg?logo=docker&label=pulls&logoColor=white)](https://hub.docker.com/r/jcs090218/jcs-emacs)
<a href="https://jcs-emacs.github.io/"><img align="right" src="https://raw.githubusercontent.com/jcs-emacs/badges/master/others/built-with/dark.svg" alt="Built with"></a>

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/jcs-emacs/jcs-elpa/master/docs/etc/logo/light/sink.png">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/jcs-emacs/jcs-elpa/master/docs/etc/logo/dark/sink.png">
  <img width="20%" align="right" src="">
</picture>

# docker
> Docker Image for jcs-emacs

[![Build](https://github.com/jcs-emacs/docker/actions/workflows/build.yml/badge.svg)](https://github.com/jcs-emacs/docker/actions/workflows/build.yml)

## 🔨 Usage

Step 1, clone this repo and navigate to the project path:

```sh
git clone https://github.com/jcs-emacs/docker
cd docker
```

Step 2, build docker image with target Emacs version and run interactively:

```sh
docker build -t jcs-emacs ./27.x/
```

This will build docker image with Emacs `27.x` version installed.

## 🛠️ Contribute

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Donate on paypal](https://img.shields.io/badge/paypal-donate-1?logo=paypal&color=blue)](https://www.paypal.me/jcs090218)
[![Become a patron](https://img.shields.io/badge/patreon-become%20a%20patron-orange.svg?logo=patreon)](https://www.patreon.com/jcs090218)

If you would like to contribute to this project, you may either clone and make pull
requests to this repository. Or you can clone the project and establish your own
branch of this tool. Any methods are welcome!

## ⚜️ License

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.

See [`LICENSE`](./LICENSE) for details.
