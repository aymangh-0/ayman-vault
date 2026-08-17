# Releases

This folder is a **local staging and reference area only**. It is not where downloads come from.

**Public downloads are attached to [GitHub Releases](../../../releases)** — installer files
(`.exe`, `.msi`) are never committed to this repository. The root `.gitignore` blocks those
extensions, so a large binary cannot be added here by accident even if one is copied in for
staging.

Nothing has been staged here yet.

## Release checklist

For each public release:

1. Build the Windows installers from the private development repository
2. Verify the version in the built installer matches the intended release version
3. Install from the built artifact and smoke-test it on a clean vault
4. Update `CHANGELOG.md` with the user-visible changes
5. Update `README.md` if features or limitations changed
6. Tag the release and attach the `.msi` and `.exe` files to the GitHub Release
7. Note in the release description that the installers are unsigned
