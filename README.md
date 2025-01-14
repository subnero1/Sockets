# Sockets

Experimental fix for [JuliaLang/julia#57001](https://github.com/JuliaLang/julia/issues/57001). This package is meant to be a drop-in replacement for the `Sockets` package in the standard library. To use, simply remove the dependency on the standard library package if present, and then run `add https://github.com/subnero1/Sockets` in package mode.

**Note:** This package is based on the v1.10.5 version of the stdlib Sockets package.