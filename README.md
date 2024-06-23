# sysprune

A post-upgrade script for [OpenBSD](https://www.openbsd.org/), to
(optionally) clean out old cruft, in a safe manner

## Requirements

1. **OpenBSD**
2. **sysclean**
3. A newly-upgraded OpenBSD system.

## Usage

```
Usage: sysprune [-h] [DIRECTORY]
Prune old files and save backups to DIRECTORY. If no DIRECTORY is specified,
sysprune will default to /opt/backup. DIRECTORY must exist for sysprune to
function.

  -h    print this message and exit
```

## Bugs

Surely.

## License

sysprune is released under the [BSD license](https://opensource.org/licenses/BSD-3-Clause).

