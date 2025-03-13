Containers for GitHub Actions
=============================

> [!NOTE]
> Work in Progress


### Example

```yaml
jobs:
  build:
    runs-on: ... # [ubunu-24.04|ubunu-24.04-arm]
    container: 
      image: ghcr.io/gbraad-actions/fedora:stable
      options: --privileged
    steps:
```
