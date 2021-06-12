
# Kha for Actions

This action sets up a [kha](https://github.com/Kode/Kha) environment for use in your workflows.

## Usage

```yaml
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: tong/kha-action@v0.1.0
        with:
          target: "linux"
          graphics: "opengl"
          compile: "true"
```