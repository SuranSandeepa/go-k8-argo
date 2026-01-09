<img width="1540" height="648" alt="image" src="https://github.com/user-attachments/assets/e8fa6f3a-db82-43bf-bd3b-89358eb3bd7a" />


- **Automated Scaling:** Change `replicaCount` in `values.yaml` and watch ArgoCD scale the pods instantly.
- **Self-Healing:** If a Kubernetes deployment is manually deleted, ArgoCD automatically recreates it to match the Git state.
- **Environment Agnostic:** Uses Helm templates to ensure the app can be deployed to Dev, Staging, or Prod by simply changing values.
