# Ministry of Elsewhere downloads

`Ministry-of-Elsewhere-0.8.0-Beta-1-arm64.dmg` is the first development-preview
DMG. It was built from `haddeeann/two-hundred-crappy-words` commit `f415c7e` for
Apple Silicon and macOS 13 or later.

The contained application is ad-hoc signed and its signature verifies locally. It
is not signed with a Developer ID certificate and is not Apple-notarized. The
product page must keep that distinction visible until a verified release replaces
this file.

Before deployment, verify the artifact with:

```sh
shasum -a 256 -c Ministry-of-Elsewhere-0.8.0-Beta-1-arm64.dmg.sha256.txt
```

Expected SHA-256:

```text
ff646eca2f1f7413079e8bc970682d5053c301295e6594a3c6fb82d252a7f76f
```
