# *Computing evolved.*
Open specifications/standards for modern computing, by the Wild Blue product development group

In this document:
- [*Computing evolved.*](#computing-evolved)
- [All specifications](#all-specifications)
- [Open implementations](#open-implementations)

© 2022 Wild Blue Ventures Inc.

Documentation, including comments in source code, is licensed under the [Creative Commons Attribution 4.0 International License](LICENSE.txt).

Source code, including snippets in documentation, is licensed under the [Apache License 2.0](CODE%20LICENSE.txt).

The preceding intellectual property notices apply to all content in this directory/repository and sub-directories, except where otherwise noted.

# All specifications
Currently proprietary specs are *italicized*. Generally, a spec is proprietary if it's inseparable from an implementation that has (or may have) business value. Proprietary specs may be available as patents.
- Scalar data encodings
  - Quants: Text scalars optimized for people to read and write (includes a survey of historical written quantities)
    - BinWords: Fast reversible encodings of binary in natural language
    - EVADat user dialect
  - LexDat: Scalar encodings with useful lexicographical orders
    - LexText: Text scalars with useful lexicographic orders and other considerations
    - *LexBin*: Binary scalars with useful lexicographic orders
  - EVADat: Text scalars for Voice Attack (Windows) software IO
- Data structure encodings
  - JOML: More obvious, more minimal TOML
  - SepVal: Generalization (and simplification) of comma separated values / IETF RFC 4180
  - *Graphite*
- Data embedding (escape techniques)
  - *MDMacro*
- Databases
  - [Hugo](https://gohugo.io/)DB
  - *MDDB*
  - 🦕 *BrontoDB*
- Cross-platform procedures
  - 📞 *CallAll*
- High performance stateful processing
  - 🌀 *Inbound*
- Addendum: Intellectual property
  - Protecting valuable IP: Patents, NDAs, and trademarks
  - Freeing ideas: CC Attribution
  - Freeing code (incompatible with patents/NDAs): Apache

# Open implementations
- [BinWords](/Data/BinWords/)
- [JOML](/Struct/JOML/)
- [SepVal](/Struct/SepVal/)