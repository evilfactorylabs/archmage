# archmage

This repository exists to keep track of every application running and operated by evilfactorylabs. If you're already familiar with Kubernetes,
well, you ain't.

## Clusters

The main ArgoCD cluster runs on DOKS in Singapore regions. The UI is only accessible via Tailscale and any inter-cloud connections
done through a VPN. The clusters are:

### ArgoCD (don't interact with this directly)

- ArgoCD UI: argocd-server.argocd.svc.cluster.local
- Control Plane API: kubernetes.default.svc.cluster.local:443

### heavy-rotation

- ArgoCD UI (proxy): heavy-rotation.duck-map.ts.net
- Control Plane API: 100.82.46.81:443
