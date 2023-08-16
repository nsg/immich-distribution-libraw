# LibRaw packaged for Immich Distribution

[LibRaw](https://www.libraw.org/) is a library for processing RAW images from digital cameras that I use in [Immich Distribution](https://github.com/nsg/immich-distribution). This repo is used as a dependency of the Immich Distribution project and is not intended for direct consumption.

## Usage

```yaml
stage-snaps:
    - immich-distribution-libraw/latest/stable
```

## Contents
```
.
├── meta
│   └── snap.yaml
└── usr
    ├── include
    │   └── libraw
    │       ├── libraw_alloc.h
    │       ├── libraw_const.h
    │       ├── libraw_datastream.h
    │       ├── libraw.h
    │       ├── libraw_internal.h
    │       ├── libraw_types.h
    │       └── libraw_version.h
    └── lib
        ├── libraw.a
        ├── libraw.la
        ├── libraw_r.a
        ├── libraw_r.la
        ├── libraw_r.so -> libraw_r.so.23.0.0
        ├── libraw_r.so.23 -> libraw_r.so.23.0.0
        ├── libraw_r.so.23.0.0
        ├── libraw.so -> libraw.so.23.0.0
        ├── libraw.so.23 -> libraw.so.23.0.0
        ├── libraw.so.23.0.0
        ├── pkgconfig
        │   ├── libraw.pc
        │   └── libraw_r.pc
        └── x86_64-linux-gnu
            ├── libgomp.so.1 -> libgomp.so.1.0.0
            ├── libgomp.so.1.0.0
            ├── libjpeg.so.8 -> libjpeg.so.8.2.2
            ├── libjpeg.so.8.2.2
            ├── liblcms2.so.2 -> liblcms2.so.2.0.8
            └── liblcms2.so.2.0.8
```
