# risadams/scoop-bucket

A [Scoop](https://scoop.sh) bucket for [Janus](https://github.com/risadams/Janus), a local proxy for Claude Code.

```powershell
scoop bucket add risadams https://github.com/risadams/scoop-bucket
scoop install risadams/janus
```

`scoop update janus` brings each new stable release. The manifest installs the release's own archive, checked against its `checksums.txt`.

The manifest is written by Janus's release workflow on each stable release; a change made here by hand is lost at the next one. Report problems in [risadams/Janus](https://github.com/risadams/Janus/issues).
