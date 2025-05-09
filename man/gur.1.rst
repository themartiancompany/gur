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
gur
=====

---------------------------------------
Ur Github HTTP mirrors management tool
---------------------------------------
:Version: gur |version|
:Manual section: 1

Synopsis
========

gur *[options]* *command* *key* *value*

Description
===========

Retrieves information about public or
private Ur mirror and checks whether they
are conformant to the format.

Commands
=========

* get                   Reads the value for the selected key.  
    *key*
      (*package*)

* check                 Checks whether the selected key (or
    *key*               all if none) has been correctly set for
      (*package*)       the package mirror.

Keys
==========

* repos                 Returns all Ur repos in the
                        target namespace.
* description           Description of mirror repository.
* homepage              Homepage of a mirror repository.
* topics                Topics of a mirror repository.

Values
========

* package_name          An Ur package name (mirrors
                        have same name with just the
                        extra *-ur* suffix).

Options
========

-N namespace            Target namespace for the Ur
                        repositories.
-W cache_dir            Location where to temporary store
                        resources.

-h                      This message.
-c                      Enable color output
-v                      Enable verbose output


Copyright
=========

Copyright Pellegrino Prevete. AGPL-3.0.

See also
========

* ur
* fur

.. include:: variables.rst
