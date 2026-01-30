# Stuff needed to build for vili

### Init Your ROM's Manifest. For example:

```
repo init -u https://github.com/DerpFest-AOSP/android_manifest.git -b 16.2 --git-lfs
```

### Clone Repository

```
git clone https://github.com/AOSP-for-vili/local_manifests.git -b 16.2 .repo/local_manifests
```

### Start Syncing

```
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune --current-branch -j$(nproc --all)
```
