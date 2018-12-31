# helmfile based stack

$ helm plugin install https://github.com/rimusz/helm-tiller
$ helm init --client-only
$ helm tiller start
$ helm sync

