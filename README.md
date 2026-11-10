# patchSight – distribution

Published artifacts of patchSight by IT sure. No source code.

| File | Content | Updated |
|---|---|---|
| `builds.json` | Latest cumulative update (UBR) per Windows build and patch month, clients and servers separately, with end of support | daily by pipeline, from the MSRC security update API |

A patchSight instance reads `builds.json` via `PatchSight__BuildListUrl`. Only lists that pass validation against the previous version are published.
