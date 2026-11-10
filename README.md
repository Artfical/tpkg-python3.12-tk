# python3.12-tk

tkinter for Python 3.12: the Tk graphical toolkit (needs the X server of the xorg package: tos-x), with turtle

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install python3.12-tk
```

| | |
|---|---|
| Version | 3.12.16 |
| Licence | PSF-2.0 |
| Upstream | https://docs.python.org/3/library/tkinter.html |
| Needs | [`python3.12`](https://github.com/Artfical/tpkg-python3.12), [`tcltk`](https://github.com/Artfical/tpkg-tcltk) |
| Needs tOS build | 618 or newer |
| Size | 146748 bytes (581867 unpacked) |
| SHA-256 of the `.tpkg` | `90efaf73fe2c7959eb56f6911bbe98d957f4f8346f1b48fb3b7ac604c2025532` |

## Commands it adds

| Command | Runs |
|---|---|
| - | - |

## Download

The package file (`python3.12-tk-3.12.16.tpkg`) and the sources it was built from are the assets of the
[v3.12.16 release](https://github.com/Artfical/tpkg-python3.12-tk/releases/tag/v3.12.16).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `Python-3.12.16.tar.xz`

Check a download: `sha256sum python3.12-tk-3.12.16.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: PSF-2.0. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
