..
   SPDX-License-Identifier: AGPL-3.0-or-later

   ----------------------------------------------------------------------
   Copyright © 2024, 2025  Pellegrino Prevete

   All rights reserved
   ----------------------------------------------------------------------

   This program is free software: you can redistribute it and/or modify
   it under the terms of the GNU Affero General Public License as published by
   the Free Software Foundation, either version 3 of the License, or
   (at your option) any later version.

   This program is distributed in the hope that it will be useful,
   but WITHOUT ANY WARRANTY; without even the implied warranty of
   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
   GNU Affero General Public License for more details.

   You should have received a copy of the GNU Affero General Public License
   along with this program.  If not, see <https://www.gnu.org/licenses/>.


=====
evmfs
=====

-------------------------------------
Ethereum Virtual Machine File System
-------------------------------------
:Version: evmfs |version|
:Manual section: 1

Synopsis
========

evmfs *[options]* *command* *[files]*

Description
===========

evmfs is the reference implementation of the
Ethereum Virtual Machine File System (EVMFS),
a distributed, undeletable, uncensorable,
network-indipendent file system running
on Ethereum Virtual Machine (EVM) compatible
blockchain networks.

Commands
=========

* get
* publish

Options
========

-o output_file          Name of the file in which to save
                        the downloaded resource.
-A fs_address           Address of the EVM file system
                        on the network.
-B ll_address           Address of the Length Lock contract
                        on the network.
-V fs_version           Version of the target EVM file
                        system.
-u                      Whether to retrieve file system
                        address from user directory or custom
                        deployment.
-d deployments_dir      Contracts deployments directory.
-N wallet_name>         Wallet name.
-w wallet_path>         Wallet path.
-p wallet_password>     Wallet password.
-s wallet_seed          Wallet seed path.
-n network              EVM network name (${_networks[*]}).
-k api_key              Etherscan-like service key.
-m call_method          Can be standalone or 'bulk'.
-r retries_max          Maximum number of retries before
                        failing.
-P tasks_parallel       Tasks to perform in parallel.
-W cache_dir            Location where to temporary store
                        the downloaded resource chunks.

-h                      This message.
-c                      Enable color output
-v                      Enable verbose output


Copyright
=========

Copyright Pellegrino Prevete. AGPL-3.0.

See also
========

* evmfs -h
* evmfs-get
* evmfs-publish

.. include:: variables.rst
