# Reusable workflow
## docker-build

```yaml
jobs:
  docker-build:
    uses: kalioz-github-actions/github-actions/.github/workflows/reusable_docker_build.yaml@cloiselet/reusable-workflow-docker-build
    with:
      context: "."
      dockerfile: "Dockerfile"
      # use_docker_in_docker: false # quicker build, but need to be used in self-hosted runners.
```
