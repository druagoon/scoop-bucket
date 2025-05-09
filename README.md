# Druagoon's Scoop Bucket

[![Tests](https://github.com/druagoon/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/druagoon/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/druagoon/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/druagoon/scoop-bucket/actions/workflows/excavator.yml)

Template bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

---

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add druagoon https://github.com/druagoon/scoop-bucket
scoop install druagoon/<manifestname>
```
