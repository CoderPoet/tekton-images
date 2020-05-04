```
-kubeconfig-writer-image,gcr.io/tekton-releases/github.com/tektoncd/pipeline/cmd/kubeconfigwriter:v0.12.0@sha256:0197014d3df2f450dc1e9896f07ec277f51c1e2e84126c9df72493867b1addba,-creds-image,gcr.io/tekton-releases/github.com/tektoncd/pipeline/cmd/creds-init:v0.12.0@sha256:632e1870f8188dcb9977cfa4be681246ef9ceb2795731cd67c83dacd931c0625,-git-image,

gcr.io/tekton-releases/github.com/tektoncd/pipeline/cmd/git-init:v0.12.0@sha256:b3cf4f912c58115e1ba9eb44a1e2d7a61445337e83117eeaec0eddbaf04ecf03

,-entrypoint-image,

gcr.io/tekton-releases/github.com/tektoncd/pipeline/cmd/entrypoint:v0.12.0@sha256:67f93630931aae98f449b5dfb764d80f7ada7c3c67950c1563ed4ec406fad2f9

,-imagedigest-exporter-image,

gcr.io/tekton-releases/github.com/tektoncd/pipeline/cmd/imagedigestexporter:v0.12.0@sha256:e10990d20d14e45311c22cc3df228bdfbfcf708db3f83124efc0ea6f50ea2fd0

,-pr-image,

gcr.io/tekton-releases/github.com/tektoncd/pipeline/cmd/pullrequest-init:v0.12.0@sha256:1f989b77e3bbd6813d2451f90b3364c0e09448d0eb976da0634eb028f9dc8a5b

,-build-gcs-fetcher-image,

gcr.io/tekton-releases/github.com/tektoncd/pipeline/vendor/github.com/googlecloudplatform/cloud-builders/gcs-fetcher/cmd/gcs-fetcher:v0.12.0@sha256:4d7b59810918f27f04df4b4a10a41c19ba04668196f33313019b170d8b331625,

-nop-image,

tianon/true@sha256:009cce421096698832595ce039aa13fa44327d96beedb84282a69d3dbcf5a81b

,-shell-image,busybox@sha256:a2490cec4484ee6c1068ba3a05f89934010c85242f736280b35343483b2264b6,

-gsutil-image,

google/cloud-sdk@sha256:6e8676464c7581b2dc824956b112a61c95e4144642bec035e6db38e3384cae2e
```


## image list


gcr.io/tekton-releases/github.com/tektoncd/pipeline/cmd/kubeconfigwriter:v0.12.0@sha256:0197014d3df2f450dc1e9896f07ec277f51c1e2e84126c9df72493867b1addba

gcr.io/tekton-releases/github.com/tektoncd/pipeline/cmd/creds-init:v0.12.0@sha256:632e1870f8188dcb9977cfa4be681246ef9ceb2795731cd67c83dacd931c0625

gcr.io/tekton-releases/github.com/tektoncd/pipeline/cmd/git-init:v0.12.0@sha256:b3cf4f912c58115e1ba9eb44a1e2d7a61445337e83117eeaec0eddbaf04ecf03


gcr.io/tekton-releases/github.com/tektoncd/pipeline/cmd/entrypoint:v0.12.0@sha256:67f93630931aae98f449b5dfb764d80f7ada7c3c67950c1563ed4ec406fad2f9

gcr.io/tekton-releases/github.com/tektoncd/pipeline/cmd/imagedigestexporter:v0.12.0@sha256:e10990d20d14e45311c22cc3df228bdfbfcf708db3f83124efc0ea6f50ea2fd0

gcr.io/tekton-releases/github.com/tektoncd/pipeline/cmd/pullrequest-init:v0.12.0@sha256:1f989b77e3bbd6813d2451f90b3364c0e09448d0eb976da0634eb028f9dc8a5b

<!-- todo  -->
gcr.io/tekton-releases/github.com/tektoncd/pipeline/vendor/github.com/googlecloudplatform/cloud-builders/gcs-fetcher/cmd/gcs-fetcher:v0.12.0@sha256:4d7b59810918f27f04df4b4a10a41c19ba04668196f33313019b170d8b331625

tianon/true@sha256:009cce421096698832595ce039aa13fa44327d96beedb84282a69d3dbcf5a81b

busybox@sha256:a2490cec4484ee6c1068ba3a05f89934010c85242f736280b35343483b2264b6

google/cloud-sdk@sha256:6e8676464c7581b2dc824956b112a61c95e4144642bec035e6db38e3384cae2e


