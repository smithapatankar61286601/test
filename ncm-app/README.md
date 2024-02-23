# ncm-app

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] ncm-app`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree ncm-app`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init ncm-app
kpt live apply ncm-app --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
