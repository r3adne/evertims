# EVERTims Ray-tracing Software

This repository holds the sources of the EVERTims raytracing client and the libevert (C library on which evertims relies for raytracing routines)

## Build

Run the build scripts in the ./build directory


### r3adne/evertims
is a forked version of EVERTims/evertims. I am adding some extra functionality:

* frequency-dependant gain in air absorption calculation
* warning user when gain is greater than 1.f or less than 0.f but not prohibiting it (This will lead to instability but it could be fun for cases when users want extreme effects)
* the ability to name saved IR files and specify their path
* creating a host VST plugin
