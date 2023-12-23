# capten-templates
Repo to manage Capten Stack Templates.

# capten-templatesss

* [apps/](./capten-templates/apps)\
* [cicd/](./capten-templates/cicd)\
  * [tekton/](./capten-templates/cicd/tekton)
    * [argocd-apps/](./capten-templates/cicd/tekton/argocd-apps)
      * [charts/](./capten-templates/cicd/tekton/argocd-apps/charts)\
      * [templates/](./capten-templates/cicd/tekton/argocd-apps/templates)
        * [configs/](./capten-templates/cicd/tekton/argocd-apps/templates/configs)
        * [pipelines/](./capten-templates/cicd/tekton/argocd-apps/templates/pipelines)
      * [Chart.yaml](./capten-templates/cicd/tekton/argocd-apps/Chart.yaml)
      * [values.yaml](./capten-templates/cicd/tekton/argocd-apps/values.yaml)
    * [tekton-pipelines/](./capten-templates/cicd/tekton/tekton-pipelines)
      * [terraform/](./capten-templates/cicd/tekton/tekton-pipelines/terraform)
        * [pipeline.yaml](./capten-templates/cicd/tekton/tekton-pipelines/terraform/pipeline.yaml)
        * [pipelinerun.yaml](./capten-templates/cicd/tekton/tekton-pipelines/terraform/pipelinerun.yaml)
        * [task.yaml](./capten-templates/cicd/tekton/tekton-pipelines/terraform/task.yaml)
    * [tekton-source/](./capten-templates/cicd/tekton/tekton-source)
      * [chart.yaml](./capten-templates/cicd/tekton/tekton-source/chart.yaml)
    * [tekton-main-app.yaml](./capten-templates/cicd/tekton/tekton-main-app.yaml)
* [infra/](./capten-templates/infra)
  * [clusters/](./capten-templates/infra/clusters)
    * [argocd-apps/](./capten-templates/infra/clusters/argocd-apps)
      * [charts/](./capten-templates/infra/clusters/argocd-apps/charts)
      * [templates/](./capten-templates/infra/clusters/argocd-apps/templates)
        * [cluster-configs/](./capten-templates/infra/clusters/argocd-apps/templates/cluster-configs)
        * [dev/](./capten-templates/infra/clusters/argocd-apps/templates/dev)
        * [prod/](./capten-templates/infra/clusters/argocd-apps/templates/prod)
      * [Chart.yaml](./capten-templates/infra/clusters/argocd-apps/Chart.yaml)
      * [values.yaml](./capten-templates/infra/clusters/argocd-apps/values.yaml)
    * [dev/](./capten-templates/infra/clusters/dev)
      * [dev-eks.yaml](./capten-templates/infra/clusters/dev/dev-eks.yaml)
    * [prod/](./capten-templates/infra/clusters/prod)
    * [clusters-main-app.yaml](./capten-templates/infra/clusters/clusters-main-app.yaml)
  * [crossplane/](./capten-templates/infra/crossplane)
    * [argocd-apps/](./capten-templates/infra/crossplane/argocd-apps)
      * [charts/](./capten-templates/infra/crossplane/argocd-apps/charts)
      * [templates/](./capten-templates/infra/crossplane/argocd-apps/templates)
        * [provider-configs/](./capten-templates/infra/crossplane/argocd-apps/templates/provider-configs)
      * [.helmignore](./capten-templates/infra/crossplane/argocd-apps/.helmignore)
      * [Chart.yaml](./capten-templates/infra/crossplane/argocd-apps/Chart.yaml)
      * [values.yaml](./capten-templates/infra/crossplane/argocd-apps/values.yaml)
    * [crossplane-config/](./capten-templates/infra/crossplane/crossplane-config)
      * [provider.yaml](./capten-templates/infra/crossplane/crossplane-config/provider.yaml)
      * [providerconfig.yaml](./capten-templates/infra/crossplane/crossplane-config/providerconfig.yaml)
    * [packages/](./capten-templates/infra/crossplane/packages)
      * [k8s/](./capten-templates/infra/crossplane/packages/k8s)
        * [definition.yaml](./capten-templates/infra/crossplane/packages/k8s/definition.yaml)
        * [eks.yaml](./capten-templates/infra/crossplane/packages/k8s/eks.yaml)
    * [providers/](./capten-templates/infra/crossplane/providers)
      * [chart.yaml](./capten-templates/infra/crossplane/providers/chart.yaml)
    * [README.md](./capten-templates/infra/crossplane/README.md)
    * [crossplane-main-app.yaml](./capten-templates/infra/crossplane/crossplane-main-app.yaml)
* [README.md](./capten-templates/README.md)
