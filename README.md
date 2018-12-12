
[![Build Status](https://travis-ci.org/lindig/polly.svg?branch=master)](https://travis-ci.org/lindig/polly)

# Polly (Work in Progress)

Polly is an [OCaml] binding for the Linux epoll system call:

* Small, simple, and self-contained
* Avoids most allocation in the event loop 
* MIT licensed

# Other Epoll Bindings

* [OCaml Backpack](https://github.com/jimenezrick/ocaml-backpack/)
* [Jane Street Core](https://github.com/janestreet/core)

# Todo

* Update dependencies in opam file
* Document interface
* Expose `Epoll.mod`
* Improve `main.ml` for testing.

If you find this useful, please contribute back by raising pull
requests for improvements you made.

[Travis]: https://www.travis-ci.org/
[OCaml]:  https://www.ocaml.org/
