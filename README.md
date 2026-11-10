# Sony PSY-Q SDK releases

The PSY-Q compiler releases from mkst/esa `psyq-binaries` (3.3 to 4.6) and the PSY-Q 4.5 headers and libraries from FoxdieTeam/psyq_sdk at commit 91719fa5.

Release `2026-11-10` holds the files byte for byte as their upstream served them,
so every sha256 below is the one recompile-toolchains and rebrew pin.

| Asset | Upstream URL | sha256 | Bytes | Pinned by |
|---|---|---|---|---|
| `psyq3.3.tar.gz` | https://github.com/mkst/esa/releases/download/psyq-binaries/psyq3.3.tar.gz | `6acc5bf3a2e406c35ec77b63f6f77986a2d61502906967f0f32ea75911e7f16f` | 1,016,863 | `psyq-3.3`, `psyq-3.3-daze-0.3.0` |
| `psyq3.5.tar.gz` | https://github.com/mkst/esa/releases/download/psyq-binaries/psyq3.5.tar.gz | `0f9dff42081ad3cc3a1e2f740797b99c28657c3cfe6406deb9de4d176bd5387e` | 1,062,923 | `psyq-3.5`, `psyq-3.5-daze-0.3.0` |
| `psyq3.6.tar.gz` | https://github.com/mkst/esa/releases/download/psyq-binaries/psyq3.6.tar.gz | `9445f4cd871ca85b764b8d2746b6122750af17ecfe2d6e8aae41d15461d8c41d` | 2,306,488 | `psyq-3.6`, `psyq-3.6-daze-0.3.0` |
| `psyq4.0.tar.gz` | https://github.com/mkst/esa/releases/download/psyq-binaries/psyq4.0.tar.gz | `f25a4f6f044eb1b344bbbd3291aa9a4fc1a1124fc637eae9522c0a117d940e28` | 2,391,794 | `psyq-4.0` |
| `psyq4.1.tar.gz` | https://github.com/mkst/esa/releases/download/psyq-binaries/psyq4.1.tar.gz | `2a2650ceb5eaa73fdc581bec4a85ccaa6ff9eeea8a4810be25a638f3cd2ebac4` | 1,780,674 | `psyq-4.1` |
| `psyq4.3.tar.gz` | https://github.com/mkst/esa/releases/download/psyq-binaries/psyq4.3.tar.gz | `577038d66507d3aa5423de0ba3f540e121a4f60f637f4794aa4350135d4f9a46` | 1,638,876 | `psyq-4.3` |
| `psyq4.4.tar.gz` | https://github.com/mkst/esa/releases/download/psyq-binaries/psyq4.4.tar.gz | `72e73934bab0d51933eb95af514afb14f3d432f01530eac3ddb16dfbb57ab66c` | 1,911,982 | `psyq-4.4` |
| `psyq_sdk-91719fa5bdca.tar.gz` | https://codeload.github.com/FoxdieTeam/psyq_sdk/tar.gz/91719fa5bdca0b7e55c5c4b9e045da407db93510 | `495697696a3288866d83ff7b7aff423560ffaffd3e212274417f3348cc0b29f8` | 5,897,525 | `psyq-4.5` |
| `psyq4.6.tar.gz` | https://github.com/mkst/esa/releases/download/psyq-binaries/psyq4.6.tar.gz | `635603e09a452c9c2923492fea8b8eb051959dd94f240933b88e94866814b894` | 2,367,287 | `psyq-4.6` |

## Source & provenance

- Retrieved 2026-11-10 from the upstream URLs above; each file's sha256 matched
  its pin before it was kept.
- Licence: proprietary (SN Systems / Sony). Kept unchanged for preservation and binary-matching work.
