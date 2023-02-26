[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/block-buster-app)](https://artifacthub.io/packages/search?repo=block-buster-app)


# block-buster-helm-app

1. This repo contains an helm artefact which will be linked to a repo in ArtifactHub. 
2. This is used for FluxCD Demo.
3. Chart Name - `block-buster-helm-app`
4. URL - `https://sidd-harth.github.io/block-buster-helm-app`
5. Container Image - `siddharth67/block-buster-dev:7.6.0`

### Sample values.yaml
```yaml
replicaCount: 1

service:
  type: NodePort

namespace:
  name: 6-demo
  
labels:
  app:
    name: block-buster
    version: 7.6.0
    env: dev
```
