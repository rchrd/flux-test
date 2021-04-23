# flux-test

Create cluster
```
k3d cluster create
```

Install Flux
```
flux install --export | kubectl apply -f -
```

Apply initial configuration
```
kubectl apply -f bootstrap/
```
