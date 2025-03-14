Containers for GitHub Actions
=============================

> [!NOTE]
> Work in Progress


## Example

### Fedora 41
```yaml
jobs:
  build:
    runs-on: ... # [ubunu-24.04|ubunu-24.04-arm]
    container: 
      image: ghcr.io/gbraad-actions/fedora:stable
      options: --privileged
    steps:
```

### CentOS Stream9
```yaml
jobs:
  build:
    runs-on: ... # [ubunu-24.04|ubunu-24.04-arm]
    container: 
      image: ghcr.io/gbraad-actions/centos:stable
      options: --privileged
    steps:
```
