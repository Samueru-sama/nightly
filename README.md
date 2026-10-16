# ScarletNX nightly builds

Builds of [ScarletNX](https://github.com/scarletnx/ScarletNX), published by its
[publish workflow](https://github.com/scarletnx/ScarletNX/blob/main/.github/workflows/publish.yml):

- **Nightlies**, `nightly-<date>-<commit>`: each push to `main` that builds everywhere. The newest 30 are kept, and
  [the latest](https://github.com/scarletnx/nightly/releases/latest) is always the newest.
- **Pull requests**, `pr-<number>`: the builds of an open pull request, replaced at each push to it and deleted when
  it closes. They are prereleases, not reviewed releases.

Each release's notes say which file is for which system, what changed and where its source is. This repository holds
only the releases: the code is in [scarletnx/ScarletNX](https://github.com/scarletnx/ScarletNX).
