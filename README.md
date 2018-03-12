# Fwloader Snap

[![Snap Status](https://build.snapcraft.io/badge/medols/fwloader.svg)](https://build.snapcraft.io/user/medols/fwloader)

## Snap content

Firmware and bitstream loader for ZTEX USB-FPGA Modules.

## Install on amd64

```shell
   $ sudo snap install fwloader --candidate --devmode
```

## Install on armhf

```shell
   $ sudo snap install fwloader --stable --devmode
```

## Upgrade on amd64

```shell
   $ sudo snap refresh fwloader --candidate --devmode
```

## Upgrade on armhf

```shell
   $ sudo snap refresh fwloader --stable --devmode
```

## Usage

```shell
   $ sudo fwloader -f -uu <firmware_file> -uf <bitstream_file>
```

