# helm-charts

Self-hosted Helm chart repo deployed via GitHub pages.

## Releases

Please refer to the [index](https://github.com/rtasalem/helm-charts/blob/gh-pages/index.yaml) for details on all Helm charts in this repository.

## Add Helm chart to repository

1. Clone repository:
```
git clone https://github.com/rtasalem/helm-charts.git
```
2. Check out to `gh-pages` branch:
```
git checkout gh-pages
```
3. Copy Helm chart into `charts` directory.
4. Puch to the `gh-pages` branch.
5. GitHub Actions will take care of releasing and deplying GitHub pages.

## GitHub Action

The GitHub action that handles deployments and releases for publishing Helm charts is taken from the [Helm docs](https://helm.sh/docs/howto/chart_releaser_action/#github-actions-workflow).