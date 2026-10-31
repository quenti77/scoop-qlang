# scoop-qlang

[Scoop](https://scoop.sh) bucket for [qlang](https://github.com/quenti77/qlang) (Windows, x64).

```powershell
scoop bucket add qlang https://github.com/quenti77/scoop-qlang
scoop install qlang
qlang --version
```

`bucket/qlang.json` is written by the release workflow of qlang (`scripts/update-package-repos.sh`). Do not edit it
by hand; change `packaging/qlang.scoop.json.in` in qlang.
