# DEPRECATED

源仓库[mritd/docker-library](https://github.com/mritd/docker-library) 已经停止维护，开始采用新的同步工具自动完成构建，可移步 [mritd/gcr](https://github.com/mritd/gcr)

# docker-library



## Kubernetes 镜像同步



目前支持版本：

* Kubernetes v1.10.3
* Kubernetes v1.11.0


## 查看gcr.io官方镜像

在科学上网的情况下，打开 https://console.cloud.google.com/gcr/images/google-containers/GLOBAL ，在右边的“过滤条件“中输入关键词来搜索。

然后再选择正确的镜像。

通常，gcr.io官方镜像的命名规则为： 
gcr.io/google_containers/IMAGE_NAME:IMAGE_TAG

比如： 
gcr.io/google_containers/kube-apiserver-amd64:v1.10.3
