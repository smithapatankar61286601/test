# helloworld-profile

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] helloworld-profile`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree helloworld-profile`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init helloworld-profile
kpt live apply helloworld-profile --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
