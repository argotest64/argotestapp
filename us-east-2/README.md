
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argotestapp.git
# cd into the cloned directory
git checkout bc8a232ccad25ffac3ecada788f8b660c06c0070
helm template . --name-template production --include-crds
```