
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argotestapp.git
# cd into the cloned directory
git checkout 6c32659385951596ee142e8477d76f313b902398
helm template . --name-template production --include-crds
```