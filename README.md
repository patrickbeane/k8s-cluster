# beane.me Kubernetes Cluster

**GitOps-driven production cluster** running:
- Gitea (`git.beane.me`)
- PostgreSQL
- Borgmatic nightly backups (pgdump)
- cert-manager for TLS (Let's Encrypt)
- nginx-ingress for routing
- Renovate + FluxCD for autonomous updates

> Public repository = Source of truth. 
> Updates flow automatically through PR -> Merge -> Flux reconcile -> Live rollout.
