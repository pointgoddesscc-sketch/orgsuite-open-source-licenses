# Working Copy Dependencies – OrgSuite Attribution Extension

**Date:** 2026-08-11  
**Source:** Working Copy iOS Git client (Settings → Licenses)  
**Purpose:** Enterprise compliance expansion of the OrgSuite Open Source Licenses Attribution system.

Working Copy is a third-party Git client used in the development workflow. Its core application is proprietary. The following open-source components are bundled and their licenses are acknowledged here for transparency and audit readiness.

## Libraries

| Component          | Description                              | Typical License              |
|--------------------|------------------------------------------|------------------------------|
| libgit2            | Stunning lib used for Git manipulation   | GPLv2 with linking exception |
| libssh2            | SSH protocol support                     | BSD-style                    |
| TreeSitter         | Incremental syntax highlighting          | MIT                          |
| highlight.js       | Syntax highlighting                      | BSD-3-Clause                 |
| GCDWebServer       | Runs the internal WebDAV server          | BSD-3-Clause                 |
| MultiMarkdown v4   | Renders markdown                         | MIT                          |
| ObjectivePGP       | Commit signing                           | MIT                          |
| SSZipArchive       | Used to work with zip files              | MIT                          |
| Asciidoctor.js     | Renders AsciiDoc preview                 | MIT                          |

## Fonts

| Font                 | Description                                      | License          |
|----------------------|--------------------------------------------------|------------------|
| DejaVu Sans Mono     | Monospace font with high Unicode coverage        | Bitstream Vera / DejaVu |
| Fira Code            | Monospace font with programming ligatures        | SIL OFL          |
| Inconsolata          | Beautiful monospace font by Raph Levien          | SIL OFL          |
| Source Code Pro      | Coding font by Paul D. Hunt                      | SIL OFL          |

## Notes for Compliance

- Full license texts are available inside the Working Copy application (tap “License” next to each entry) and in the respective upstream repositories.
- This file extends the primary attribution list maintained in `open-source-components.csv` and the live site at https://orgsuite-open-source-licenses.vercel.app.
- OrgSuite does not redistribute Working Copy itself; this is an attribution of tools used in the development environment.

---
*Generated for OrgSuite Enterprise AI / Point Goddess CC • 2026-08-11*