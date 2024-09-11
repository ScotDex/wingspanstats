# Wingspan Statistics

## Overview

- Configuration stored in `config/statsconfig.py`.
- `CORPORATION_IDS` are corporations to check for.
- `ALLIANCE_IDS` are alliances to check for.
- Make sure to change:
  - `EARLIEST` for the starting point in time.
  - `HEADERS` to represent yourself.
- Currently implemented backends:
  - DB fetcher:
    - zKillboard.
    - ESI.
  - DB parse:
    - MongoDB.

## Usage

bash
$ nano config/statsconfig.py
$ python3 wingspanstats.py
Use code with caution.

Thanks
Original Authors: farshield/wingspanstats
Rustam Gubaydullin (@second_fry)

Significant Contributors:

- ScottishDex/Dexomus Viliana
- Rustam Gubaydullin (@second_fry)
- https://github.com/ntfoster

Note:
This codebase has evolved over time, and some sections may reflect older coding practices or dependencies. The code is now considered almost fully functional, thanks to contributions from ScottishDex/Dexomus Viliana. Additional documentation is being developed to ensure the code remains maintainable and doesn't become redundant again.
