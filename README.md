# K8s High Availability

Kubernetes manifest demonstrating high-availability patterns. Single manifest file with pod anti-affinity and topology spread constraints.

## Files

| File | Purpose |
|---|---|
| `manifest.yaml` | Pod with anti-affinity + topology spread |

## Key Concepts

- **Pod anti-affinity** — Prevents pods from landing on the same node
- **Topology spread** — Evenly distributes pods across failure domains

## Quick Start

```bash
kubectl apply -f manifest.yaml
```

## Related Practice
