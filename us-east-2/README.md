
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argotestapp.git
# cd into the cloned directory
git checkout 1c893124b8165b767021acbddc6cc688db4dac04
helm template . --name-template production --include-crds
```