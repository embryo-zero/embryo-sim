# Legal notes for Embryo Sim

Embryo Sim is a modified version of **Verilator** (https://github.com/verilator/verilator), copyright its authors.
License: **LGPL-3.0-only OR Artistic-2.0 (our choice); parts under other licenses in LICENSES/**. The original license files are kept unchanged: LICENSE, LICENSES.

First lines of those files when we forked (2026-11-16):

- `LICENSE`: GNU LESSER GENERAL PUBLIC LICENSE / Version 3, 29 June 2007 / Copyright (C) 2007 Free Software Foundation, Inc. <http://fsf.org/>
- `LICENSES`: folder of license texts: Apache-2.0.txt, Artistic-2.0.txt, BSD-3-Clause.txt, CC0-1.0.txt, ISC.txt, LGPL-3.0-only.txt, LicenseRef-Altera-No-Warranty.txt, LicenseRef-IEEE-1800.txt, MIT.txt, Unlicense.txt

## When we offer it to people

- We take it under LGPL-3.0: source of the tool (and our changes) goes with any copy we hand out.
- Simulators people build with it are theirs (Verilator's own exception for generated code).
- CHECK before release: files marked LicenseRef-Altera-No-Warranty and LicenseRef-IEEE-1800 (see LICENSES/).
- Running it on our own servers for people (inside the apps) is not handing out the program; we still keep our source public.
- Chips and layouts people make with it belong to them; the tool's license does not cover what it produces.
- No warranty beyond what the license says.
