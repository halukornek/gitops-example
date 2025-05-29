# GitOps-managed Applications

This repository contains applications managed by the ArgoCD GitOps controller.

## Config map creation

```
configMapGenerator:
  - name: ${name}
    files: 
    - [array of files to be added to the config]

generatorOptions:
    disableNameSuffixHash: false
```
