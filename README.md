# check

GitHub action that simply checks if the condition is true

## Usage

If you want to check that a pull request has a milestone, do:

```yaml
steps:
  - uses: flying-sheep/check@v1
    with:
      success: ${{ github.event.pull_request.milestone != null }}
```
