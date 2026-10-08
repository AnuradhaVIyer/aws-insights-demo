# AWS Insights demo

Sample-data demo of dashboards organised around the six pillars of the AWS Well-Architected Framework.

| Pillar | Status | Page |
|---|---|---|
| Cost Optimization | Available | `cost-dashboard.html` |
| Security | Available | `security-dashboard.html` |
| Reliability | Planned | |
| Operational Excellence | Planned | |
| Performance Efficiency | Planned | |
| Sustainability | Planned | |

All data in `data/` is synthetic.

## View

Serve the folder over HTTP, then open `index.html`:

```
python -m http.server 8000
```

The pages cannot load their data when opened directly from disk. The repository can also be published with GitHub Pages (Settings, then Pages, then deploy from the main branch).

## Source

This repository is generated from a private product repository. Do not edit files here; changes are overwritten by the next build. The release shown is recorded in `DEMO_VERSION.txt`.

Pillar names follow the AWS Well-Architected Framework. AWS Insights is an independent tool and is not provided or endorsed by AWS.
