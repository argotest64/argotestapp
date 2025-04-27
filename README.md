
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argotestapp.git
# cd into the cloned directory
git checkout b39e3a838fde6655760dedf374df00655dfcc4d1
helm template . --name-template development --include-crds
```