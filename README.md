# vmondor42-iot

Manifestes Kubernetes surveillés par Argo CD (projet Inception-of-Things, partie 3).
Modifier le tag de l'image dans `manifests/deployment.yaml` (v1 <-> v2) puis pousser :
Argo CD redéploie automatiquement dans le namespace `dev`.
