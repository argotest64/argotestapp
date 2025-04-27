
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argotestapp.git
# cd into the cloned directory
git checkout 536ce18e0f1510e4c2cd90145e7bb9ae9d52205a
helm template . --name-template development --include-crds
```