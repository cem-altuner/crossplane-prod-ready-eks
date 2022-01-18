Run the following command to build package.

```
kubectl crossplane build configuration \
    --name k8s  
```

Run the following command to push your package to dockerhub.

```
kubectl crossplane push configuration \
    <your_registry>/crossplane-k8s:v0.2.14
```

> :warning: It is necessary to login docker before push the package.
