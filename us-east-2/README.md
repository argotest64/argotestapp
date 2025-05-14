
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argotestapp.git
# cd into the cloned directory
git checkout 8111731e5f99381a4670a60f2618d5a49cee7613
helm template . --name-template production --include-crds
```