# Usage

```yaml
steps:
  - uses: actions/checkout@v2

  - name: Package and publish Helm Chart
    uses: kalioz-github-action/github-actions/actions/package-helm-chart-chartmuseum@cloiselet/feat-add-helm-action
    with:
        folder: "helm/simple-webapp"
        chartmuseum_url: http://chartmuseum.chartmuseum.svc.cluster.local:8080

```