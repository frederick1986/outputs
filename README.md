# Public configuration outputs

This repository receives generated client files from separate private projects.

- `warp/`: `masque.yaml`, `usque-custom-pro.yaml`, `combined.yaml` and their manifest, produced by `warp-config-toYaml`
- `freenodes/`: collected and checked subscription files plus the health report, produced by `freeNodes_check`

Each publisher updates only its own directory and preserves the other project's files. Files appear after their corresponding workflow has been configured and completes successfully.

## Public data warning

Published WARP client YAMLs contain reusable WARP key material. Anyone can read and copy public files, Git history, forks and cached downloads. Raw account JSON, account-management tokens and workflow authentication credentials must never be published here.

This repository does not run account registration or store private account state. Node availability, country labels and service access are not guaranteed by publication.
