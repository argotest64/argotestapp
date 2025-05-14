
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argotestapp.git
# cd into the cloned directory
git checkout e715b60267e915c88943fd96dc634fc98f28f2ee
helm template . --name-template production --include-crds
```