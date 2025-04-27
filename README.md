
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argotestapp.git
# cd into the cloned directory
git checkout c852c87e8126ac218615a684ddf11b90afcc8fac
helm template . --name-template development --include-crds
```