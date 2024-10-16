# NeutronOS

## Building ##

### Initializing Repo:
```
repo init -u https://github.com/NeutronOS-CLO/platform_manifest.git -b vite --git-lfs
```

### Sync changes:
```
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```
