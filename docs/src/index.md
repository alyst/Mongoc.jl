
# Mongoc.jl

## Introduction

**Mongoc.jl** is a [MongoDB](https://www.mongodb.com/) driver for the Julia Language.

It is implemented as a thin wrapper around [libmongoc](http://mongoc.org/),
the official client library for C applications.

Given that [BSON](http://bsonspec.org/) is the document format for MongoDB,
this package also implements a wrapper around [libbson](http://mongoc.org/libbson/current/index.html),
which provides a way to create and manipulate BSON documents.

## Requirements

* MongoDB 3.0 or newer.

* Julia versions v1.5 or newer.

* Linux, macOS, or Windows.

## Installation

From a Julia session, run:

```julia
julia> using Pkg

julia> Pkg.add("Mongoc")
```

## Source Code

The source code for this package is hosted at
[https://github.com/felipenoris/Mongoc.jl](https://github.com/felipenoris/Mongoc.jl).

## License

The source code for the package **Mongoc.jl** is licensed under
the [MIT License](https://github.com/felipenoris/Mongoc.jl/blob/master/LICENSE).

This repository distributes binary assets built from
[mongo-c-driver](https://github.com/mongodb/mongo-c-driver) source code,
which is licensed under [Apache-2.0](https://github.com/mongodb/mongo-c-driver/blob/master/COPYING).

## Getting Help

If you're having any trouble, have any questions about this package
or want to ask for a new feature,
just open a new [issue](https://github.com/felipenoris/Mongoc.jl/issues).

## Contributing

Contributions are always welcome!

To contribute, fork the project on [GitHub](https://github.com/felipenoris/Mongoc.jl)
and send a Pull Request.

## References

* [libbson documentation](http://mongoc.org/libbson/current/index.html)

* [libmongoc documentation](http://mongoc.org/libmongoc/current/index.html)
