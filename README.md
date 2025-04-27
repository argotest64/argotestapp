
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argotestapp.git
# cd into the cloned directory
git checkout ef07ee94cc9f0301613ded74625157ed57f2b899
helm template . --name-template development --include-crds
```