# H3VR Documentation

This repo contains the docfx project that generates the static documentation site for the game's scripts.
This repo does NOT contain the actual documentation itself. The documentation is compiled from a decompiled project and then added to this repo at `reference/Assembly-CSharp.xml`.

## Updating the site

1. Copy the contents of `H3DIR/h3vr_Data/Managed/` to `reference/`
2. Replace `reference/Assembly-CSharp.xml` with the updated version.
3. Run `docfx doxfx_project/doxfx.json` (optionally with `--serve` to preview changes)
