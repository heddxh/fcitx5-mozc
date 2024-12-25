# Fcitx5 Mozc

The repo aims to

* Use CMake to build [original project](https://github.com/fcitx/mozc) so that it can be integrated into other platforms more easily.
* Avoid [mozc](https://github.com/google/mozc)'s huge git history when building.

It is initially created by

```sh
git filter-repo --path src/unix/fcitx5 --force
```

and [src/unix/fcitx5](./src/unix/fcitx5) will be synced from [origin](https://github.com/fcitx/mozc/tree/fcitx/src/unix/fcitx5) regularly.
