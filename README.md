# roboFont-Extension-action
RoboFont Extension builder for GitHub Actions

# Usage

```yaml
name: Validate and Build the Extension
on:
  push

jobs:
  validate_and_build:
    runs-on: ubuntu-latest
    steps:
      - name: Validate and Build
        uses: typemytype/roboFont-Extension-action@v0.1.0

```
