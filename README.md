# *Computing evolved.*
Open standards for modern computing by the Wild Blue product development group

In this file:
- [*Computing evolved.*](#computing-evolved)
  - [All standards](#all-standards)
  - [Open implementations](#open-implementations)

Copyright 2022 Wild Blue Ventures Inc.  
Documentation in this repository, which includes source code comments, is licensed under the [Creative Commons Attribution 4.0 International License](LICENSE.txt).  
Source code in this repository, which includes code snippets in documentation, is licensed under the [Apache License 2.0](CODE LICENSE.txt).

## All standards
- Scalar data encodings
  - JoyDat: Text scalars optimized for people to read and write (many options)
    - VADat: Text scalars for Voice Attack (Windows) software IO
      - VADat-Sys
      - VADat-User
  - LexDat: Scalar encodings with useful lexicographical orders
    - LexDat-Bin / LexBin: Binary scalars with useful lexicographic orders (closed standard)
    - LexDat-Text / LexText: Text scalars with useful lexicographic orders and some consideration for human users
  - BrontoCode (closed standard)
- Data structure encodings
  - JOML: More obvious, more minimal TOML
  - SepVal: Generalization (and simplification) of comma separated values / IETF RFC 4180
  - BinDoc: Binary documents (closed standard)
- Databases
  - JoyDB: Databases for people
    - JoyDB + Hugo
      - JoyDB + Hugo + Bronto
- MMOS (closed standard)

## Open implementations
- JOML
- SEPVAL