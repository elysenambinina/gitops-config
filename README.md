# gitops-config

État souhaité du cluster EKS, appliqué par ArgoCD.

| Dossier | Contenu |
|---|---|
| `bootstrap/root.yaml` | Application racine (seule ressource appliquée à la main) |
| `bootstrap/apps/` | Applications actives de la plateforme |
| `bootstrap/a-activer/` | Applications activées au fil du ROADMAP |
| `projects/` | AppProjects ArgoCD |
| `apps/app-demo/` | Manifestes de l'application (base + overlays dev, staging, prod) |
| `platform/` | Configuration de la plateforme (ClusterSecretStore…) |
| `policies/kyverno/` | Catalogue de politiques et exceptions |
| `policies/tests/` | Tests `kyverno test` |
