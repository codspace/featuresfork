
# Git (from source) (git)

Install an up-to-date version of Git, built from source as needed. Useful for when you want the latest and greatest features. Auto-detects latest stable version and installs needed dependencies.

## Example Usage

```json
"features": {
    "ghcr.io/codspace/featuresfork/git:1": {}
}
```

## Options

| Options Id | Description | Type | Default Value |
|-----|-----|-----|-----|
| version | Select or enter a Git version. | string | os-provided |
| ppa | Install from PPA if available | boolean | true |



---

_Note: This file was auto-generated from the [devcontainer-feature.json](https://github.com/codspace/featuresfork/blob/main/src/git/devcontainer-feature.json).  Add additional notes to a `NOTES.md`._
