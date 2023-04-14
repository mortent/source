# source

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] source`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree source`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init source
kpt live apply source --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
