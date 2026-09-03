# Akkitto Scoop Bucket

<!-- Managed by tauridium-scoop-bucket-bootstrap -->

[![Tests](https://github.com/Akkitto/scoop-bucket-master/actions/workflows/ci.yml/badge.svg)](https://github.com/Akkitto/scoop-bucket-master/actions/workflows/ci.yml) [![Excavator](https://github.com/Akkitto/scoop-bucket-master/actions/workflows/excavator.yml/badge.svg)](https://github.com/Akkitto/scoop-bucket-master/actions/workflows/excavator.yml)

Official [Scoop](https://scoop.sh/) bucket for [Tauridium](https://github.com/Akkitto/Tauridium).

## Install

```powershell
scoop bucket add master https://github.com/Akkitto/scoop-bucket-master
scoop install master/tauridium
```

## Update

```powershell
scoop update
scoop update tauridium
```

## Uninstall

```powershell
scoop uninstall tauridium
```

## Remove the bucket

```powershell
scoop bucket rm master
```

## Notes

- The `tauridium` manifest tracks stable GitHub releases through Scoop `checkver` and `autoupdate`.
- Scoop's Excavator workflow checks for manifest updates automatically.
- Tauridium requires Microsoft Edge WebView2 Runtime; supported Windows 10 and Windows 11 installations normally already provide it.

## Upstream

- [Tauridium](https://github.com/Akkitto/Tauridium)
- [Scoop](https://github.com/ScoopInstaller/Scoop)
