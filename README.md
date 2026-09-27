# Scoop bucket for Promptline

[Promptline](https://promptline.cc) keeps your prompt library one hotkey
away, in every window.

```powershell
scoop bucket add promptline https://github.com/bekalpaslan/scoop-bucket
scoop install promptline
```

The manifest runs Promptline's own setup exe from its
[GitHub release](https://github.com/bekalpaslan/promptline/releases), so
the app installs for the current user under `%LOCALAPPDATA%\Promptline`,
the same install as the website's download, and updates itself.
`scoop uninstall promptline` runs Promptline's uninstaller.

Problems with Promptline itself go to
[bekalpaslan/promptline](https://github.com/bekalpaslan/promptline/issues).