# Wingspan Statistics

## Overview

- From my limited understanding of coding, this back end harvests a bunch of kills from Zkill and then organises them and adds to a database ready to be presented in a front end.
- The code itself is over 7 years old to the point the fashion in which you retrieve zkill API has now entirely changed im told.
- I have managed to troubleshoot, alongside some additional help, to get to the point where the zkills are now stored in a database.
- Original README stored below.
- Some additional contributions and input welcome to improve and streamline functionality.

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
- $ nano config/statsconfig.py
- $ python3 wingspanstats.py
Use code with caution.

Thanks
Original Authors: farshield/wingspanstats
Rustam Gubaydullin (@second_fry)

Significant Contributors to restore functionality:

- ScottishDex/Dexomus Viliana
- https://github.com/ntfoster
- https://github.com/loustewart

Note:

- This codebase has evolved over time, and some sections may reflect older coding practices or dependencies. The code is now considered almost fully functional, thanks to contributions from ScottishDex/Dexomus Viliana. Additional documentation is being developed to ensure the code remains maintainable and doesn't become redundant again.
