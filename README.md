# Probably.jl
_Probabilistic data structures in Julia_

[![Dev](https://img.shields.io/badge/docs-dev-blue.svg)](https://kernelmethod.github.io/Probably.jl/dev)
[![CI](https://github.com/kernelmethod/Probably.jl/workflows/CI/badge.svg)](https://github.com/kernelmethod/Probably.jl/actions?query=workflow%3ACI)
[![Codecov](https://codecov.io/gh/kernelmethod/Probably.jl/branch/master/graph/badge.svg)](https://codecov.io/gh/kernelmethod/Probably.jl)

Probably.jl provides an implementation of common probabilistic data structures that are:
- Written in pure Julia
- Both fast and memory-efficient
- Good for default or casual use cases, easy to use in other projects
- Manipulated via functions with names from Julia's Base library

This package does __not__ attempt to:
- Provide a wide array of of functionality
- Provide structures 100% optimized for different use cases
- Gloss over the limitation of the data structures. Instead, you are expected to understand in broad strokes how the data structures work before you use them.

## Package features
Probably.jl currently includes the following data structures:
 - Bloom filter
 - Cuckoo filter
 - Count-min sketch
 - HyperLogLog

## Contributing
Found a bug? Have a good idea for performance improvements? Know some sweet probabilistic data structure this package needs?

Great, any feedback is very much appreciated! Just create an Issue here on GitHub or send me an email and we'll discuss it.
