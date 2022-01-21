# *Computing evolved.*
Open specifications/standards for modern computing, by the Wild Blue product development group

In this document:
- [*Computing evolved.*](#computing-evolved)
  - [All specifications](#all-specifications)
  - [Open implementations](#open-implementations)

Copyright 2022 Wild Blue Ventures Inc.  
Documentation in this repository, which includes source code comments, is licensed under the [Creative Commons Attribution 4.0 International License](LICENSE.txt).  
Source code in this repository, which includes snippets in documentation, is licensed under the [Apache License 2.0](CODE LICENSE.txt).

## All specifications
Currently proprietary specs are *italicized*. Generally, a spec is proprietary if it's inseparable from an implementation with an active or pending patent.
- Scalar data encodings
  - JoyDat: Text scalars optimized for people to read and write (partial spec)
    - EVADat: Text scalars for Voice Attack (Windows) software IO
      - EVADat-Sys
      - EVADat-User
  - LexDat: Scalar encodings with useful lexicographical orders
    - *LexDat-Bin* / *LexBin*: Binary scalars with useful lexicographic orders
    - LexDat-Text / LexText: Text scalars with useful lexicographic orders and some consideration for human users
  - 🦕 *BrontoCode*
- Data structure encodings
  - JOML: More obvious, more minimal TOML
  - SepVal: Generalization (and simplification) of comma separated values / IETF RFC 4180
  - BinDoc: Binary documents
- Databases
  - JoyDB: Databases for people
    - JamDB: Structured data in [static sites](https://jamstack.org/)
      - Hugo JamDB
        - *Hugo + Bronto JamDB*
- Compute
  - Ⓜ️Ⓜ️ *MMOS*
- Addendum: Intellectual property
  - Protecting valuable IP: Patents, NDAs, and trademarks
  - Freeing ideas: CC Attribution
  - Freeing code (incompatible with patents/NDAs): Apache

## Open implementations
- JOML
- SepVal