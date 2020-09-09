Android Open Source Andromeda Project
========

To initialize your local repository, use this command:

	repo init -u https://github.com/aosap-tmp/platform_manifest.git -b eleven

 Then to sync up:

```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
