# helmfile based stack

# Setup
```
helm plugin install https://github.com/rimusz/helm-tiller
helm init --client-only
```

# Install
```
helm tiller run helmfile sync
```

# Delete
```
helm tiller run helmfile delete --purge
```
