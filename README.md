# `.github`

Organisation-level files for [Mooring](https://mooring.sh).

- **`profile/README.md`** — rendered as the public
  [github.com/mooring-sh](https://github.com/mooring-sh) profile page.
- **`assets/`** — brand assets, kept here so the profile does not depend on
  the website staying up.

## Brand assets

| File | Size | Use |
| --- | --- | --- |
| `assets/mooring-icon.png` | 1024×1024 | Canonical raster icon. |
| `assets/mooring-icon-512.png` | 512×512 | Smaller raster, matches the copy served at `mooring.sh`. |
| `assets/mooring-icon.svg` | vector | Source of truth for the app icon. |

The icon is generated from the app's asset catalog, so keep these in step with
`mac/Mooring/Assets.xcassets/AppIcon.appiconset` in the application repository
rather than editing them here.

## Conventions

Nothing in `profile/README.md` is version-pinned. Version-specific links —
release notes especially — live on [mooring.sh](https://mooring.sh), which is
already updated at each release. Adding a version number here would create a
second place to forget.
