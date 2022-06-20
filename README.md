> This file was generated by [README.tpl](README.tpl) via [yaml-readme](https://github.com/LinuxSuRen/yaml-readme), please don't edit it directly!

## 实用的流水线模板

这里包含一些比较实用的流水线模板。在 KubeSphere Console 编辑一个新的流水线时，我们可以选择合适的模板来填充流水线脚本。

These are offical Pipeline templates:
Template Type: ClusterStepTemplate

| Name | Description |
|---|---|
| [Docker build &amp; push](featured/steps/docker-build-push.yaml) | Build and push an image from a Dockerfile |
| [Docker login](featured/steps/docker-login.yaml) | Docker login |
| [Pipeline trigger](featured/steps/pipeline-trigger.yaml) | Pipeline trigger step |

Template Type: ClusterTemplate

| Name | Description |
|---|---|
| [Golang](featured/pipelines/golang.yaml) | Designed for the continuous integration of most Golang projects, including dependency downloading, testing, building, and artifact archiving. |
| [Maven](featured/pipelines/maven.yaml) | Designed for the continuous integration of most Maven projects, including dependency downloading, testing, building, and artifact archiving. |
| [Node.js](featured/pipelines/nodejs.yaml) | Designed for the continuous integration of most Node.js projects, including dependency downloading, testing, building, and artifact archiving. |


## Contribution

想要了解更多关于流水线模板如何工作，请参考：

- https://github.com/kubesphere/ks-devops/blob/master/docs/pipeline-template.md
- [Contribution guide](CONTRIBUTION.md)
