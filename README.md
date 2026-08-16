# seiscomp-scmag

![CI](https://github.com/platformfuzz/seiscomp-scmag/actions/workflows/ci.yml/badge.svg)
![Build and Release](https://github.com/platformfuzz/seiscomp-scmag/actions/workflows/build-and-release.yml/badge.svg)

Unofficial SeisComP scmag image built with public gsm. Not gempa-supported.

The process computes magnitudes.

**Package:** [ghcr.io/platformfuzz/seiscomp-scmag](https://github.com/platformfuzz/seiscomp-scmag/pkgs/container/seiscomp-scmag)

## Run

```bash
docker pull ghcr.io/platformfuzz/seiscomp-scmag:latest
docker run --rm ghcr.io/platformfuzz/seiscomp-scmag:latest
```

`SCMASTER_HOST`, `SEEDLINK_HOST`, and `DB_HOST` can be overridden at run time.

## Build

```bash
docker build -t seiscomp-scmag:test .
docker run --rm seiscomp-scmag:test
```
