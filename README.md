# helm-post-renderer-example
An example of using Kustomize as a Helm post-renderer

## Use Case

Though this is a very simple and contrived example, the real benefit of using Kustomize as a Helm post-renderer is the ability to modify a Helm chart's output without having to modify a third-party chart. For example, if you need to modify something in a chart that isn't possible simply using the provided values schema, this pattern will let you do that.