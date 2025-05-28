# helm-charts

Helm chart repo deployed via GitHub pages: [helm.ranasalem.io](https://helm.ranasalem.io).

GitHub repo: [github.com/rtasalem/helm-charts](https://github.com/rtasalem/helm-charts).

## Releases

Please refer to the [index.yaml](https://github.com/rtasalem/helm-charts/blob/gh-pages/index.yaml) for details on all Helm charts in this repository.

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
4. Commit changes to the `gh-pages` branch and open a PR.
5. After squashing and merging the PR, the chart releaser GitHub Action will take care of releasing and deploying published charts via GitHub pages. The `index.yaml` file will be automatically updated.

## GitHub Action

The GitHub action responsible for handling releases and deployments is taken from the [Helm docs](https://helm.sh/docs/howto/chart_releaser_action/#github-actions-workflow).

Using the chart releaser action provided by Helm, this repository has 2 branches: `main` which contains the source code for all Helm charts and `gh-pages` which hosts the published charts and the `index.yaml`.
