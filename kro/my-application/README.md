# Kro Application Instance

Basic application instance as seen [here](https://kro.run/docs/getting-started/deploy-a-resource-graph-definition)

```shell
argocd app create my-application \
--project default \
--repo https://github.com/newtondev/argocd-sandbox.git \--path kro/my-application \
--dest-namespace my-app \
--dest-server https://kubernetes.default.svc
```
