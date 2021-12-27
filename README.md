# s3_simple

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] s3_simple`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree s3_simple`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init s3_simple
kpt live apply s3_simple --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
