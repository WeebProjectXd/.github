```zsh
 mkdir weeb
```

```zsh
 cd weeb
```

```zsh
 repo init -u https://github.com/WeebProjectXd/platform_manifest -b sushi --depth=1

```
```zsh
 repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags

```

```shell
# Init
. build/envsetup.sh

# Lunch
lunch weeb_[codename]-[build type]

# Make a weeb project !
make weeb-prod -j$
```

