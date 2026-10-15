# Shogun05 Extensions

Source code is maintained in [Shogun05/extensions-source](https://github.com/Shogun05/extensions-source).

## APK builds

GitHub Actions builds all extensions, including MangaRaw, and publishes release
assets and the matching catalogue:

1. Complete the [one-time publishing setup](https://github.com/Shogun05/extensions-source/blob/add-mangaraw/.github/BUILDING.md).
2. Open [Build and publish extensions](https://github.com/Shogun05/extensions-source/actions/workflows/build_and_publish.yml).
3. After a successful publish, download APKs from [Releases](https://github.com/Shogun05/extensions/releases), or install them through Mihon.

The catalogue stays empty until the first successful publish. APKs are stored as
Release assets, not committed to this branch.

## Add to Mihon

Add this URL under extension stores:

```text
https://raw.githubusercontent.com/Shogun05/extensions/repo/index.pb
```

Use the branch URL so later publications can update the extension list.

- [MangaRaw source](https://github.com/Shogun05/extensions-source/tree/add-mangaraw/src/ja/mangaraw)
- [Report an issue](https://github.com/Shogun05/extensions-source/issues)
