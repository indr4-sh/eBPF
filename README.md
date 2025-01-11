## Download and Install eunomia-bpf Development Tools

You can download and install eunomia-bpf using the following steps:

Download the ecli tool for running eBPF programs:

```console
$ wget https://aka.pw/bpf-ecli -O ecli && chmod +x ./ecli
$ ./ecli -h
Usage: ecli [--help] [--version] [--json] [--no-cache] url-and-args
```

Download the compiler toolchain for compiling eBPF kernel code into config files or WASM modules:

```console
$ wget https://github.com/eunomia-bpf/eunomia-bpf/releases/latest/download/ecc && chmod +x ./ecc
$ ./ecc -h
eunomia-bpf compiler
Usage: ecc [OPTIONS] <SOURCE_PATH> [EXPORT_EVENT_HEADER]
....
```

Note: If you are on the aarch64 platform, please use the [ecc-aarch64](https://github.com/eunomia-bpf/eunomia-bpf/releases/latest/download/ecc-aarch64) and [ecli-aarch64](https://github.com/eunomia-bpf/eunomia-bpf/releases/latest/download/ecli-aarch64).

