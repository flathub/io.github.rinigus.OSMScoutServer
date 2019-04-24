Use local-dev branch for local builds, if needed.

* Make a symbolic link to local osmscout-server source folder.

* Run following commands to build and test local flatpak:

```
flatpak-builder --repo=../flatpak --force-clean ../flatpak-build-desktop io.github.rinigus.OSMScoutServer.json
flatpak-builder --run ../flatpak-build-desktop io.github.rinigus.OSMScoutServer.json osmscout-server
```

