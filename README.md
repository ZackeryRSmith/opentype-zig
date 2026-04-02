# opentype-zig
OpenType font parsing and generation for Zig

> [!CAUTION]  
> opentype-zig is currently under active development. The codebase is in a pre-alpha state and is not yet functional.

# Goals
- Read and write SFNT-based fonts (TTF, OTF, and bitmap)
- Full table support across all outline types
- Fast serialization and incremental rebuilds
- Simple, low-level API
- Accurate round-trip parsing and serialization

# Non-goals
- Font rendering or rasterization
- WOFF/WOFF2
- Font validation

# Acknowledgements
Inspired by [otfcc](https://github.com/caryll/otfcc), a tool for reading and building OpenType fonts. It is now deprecated and was never designed as an embeddable library. opentype-zig aims to fill that gap as a fast, embeddable Zig library.
