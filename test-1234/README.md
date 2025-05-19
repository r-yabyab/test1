# test-1234

## Description
hello world123

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] test-1234`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree test-1234`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init test-1234
kpt live apply test-1234 --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
