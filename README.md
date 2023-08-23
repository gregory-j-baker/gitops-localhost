## Argo-CD Autopilot cluster recovery

To recover a cluster using this git repository, run the `argocd-autopilot` command with the `--recover` flag.

```
export GIT_REPO=https://github.com/gregory-j-baker/gitops-localhost/
export GIT_TOKEN=ghp_xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
argocd-autopilot repo bootstrap --recover
```

## References

- <https://argocd-autopilot.readthedocs.io/en/stable/Recovery/>
- <https://argocd-autopilot.readthedocs.io/>
