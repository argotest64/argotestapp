
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argotestapp.git
# cd into the cloned directory
git checkout 44684920311ddc3d59fe4a5413b85821880d6dfa
helm template . --name-template development --include-crds
```