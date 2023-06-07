# H3VR Documentation

This repo contains the docfx project that generates the static documentation site for the game's scripts.
This repo does NOT contain the actual documentation itself. The documentation is compiled from a decompiled project and then added to this repo at `reference/Assembly-CSharp.xml`.

## Updating the site

1. Update the game assembly at `reference/Assembly-CSharp.dll` (does not need to be stripped, provided you aren't committing it to the repo)
2. Replace `reference/Assembly-CSharp.xml` with the updated version.
3. Run `docfx doxfx_project/doxfx.json` (optionally with `--serve` to preview changes)
