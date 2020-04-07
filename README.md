# Equinor Helm Charts

Repository of helm-charts published on [hub.helm.sh](https://hub.helm.sh/charts/equinor)

## Use charts from this repository directly

    helm repo add equinor-charts https://equinor.github.io/helm-charts/charts/
    helm repo update

    helm upgrade --install neo4j-community equinor-charts/neo4j-community

## Adding a chart to this repo

To add a chart to this repo, please follow the same rules as hub.helm.sh as [documented here](https://github.com/helm/hub/blob/master/Repositories.md).

**TL:DR;**

* Follow [Chart Best Practices](https://helm.sh/docs/chart_best_practices/)
* Chart must pass `ct lint` ([https://github.com/helm/chart-testing](https://github.com/helm/chart-testing)). This is enforced on PRs and commits to this repo.

## Help

If you need assistance contact me (Stian Øvrevåge) on Slack or ask in the Equinor Slack #kubernetes channel.
