# Assets
When attempting to load this repository as a Hugo module, use the GitLab mirror because Hugo modules cannot have a leading `.`.

## README
Profile README file for Codeberg / GitLab / GitHub.

| Service | Repository | Path |
| ------- | ---------- | ---- |
| Codeberg | `.profile` | `/` |
| GitLab | `gitlab-profile` | `/` |
| GitHub | `.github` | `/profile/` |

### Editing
Only modify the `source.md` file. Files `/README.md` and `/profile/README.md` are generated via the pipeline.

## Logos
Logos for projects, mostly sourced from the [Lucide icon pack](https://github.com/lucide-icons/lucide). Refer to the SPDX comments in each `source.svg` file for license information.

+ File: 24x24
+ Image: 22x22
+ PNG: 512x512

### Editing
Only modify the `source.svg` file in each directory. Files `/logos/*/logo.png` and `/logos/*/logo.svg` are generated via the pipeline.
