# gcr-sync
关联阿里云镜像仓库，用于同步gcr镜像

##  从Registry中拉取镜像

- 公网地址

```
registry.cn-zhangjiakou.aliyuncs.com/gcr-sync/[镜像仓库名称]:[镜像版本号]
```

- 经典网络（通过访问镜像仓库内网地址来加快镜像下载速度并减少公网流量开销）

```
registry-internal.cn-zhangjiakou.aliyuncs.com/gcr-sync/[镜像仓库名称]:[镜像版本号]
```

- 专有网络（VPC 机器均可访问）

```
registry-vpc.cn-zhangjiakou.aliyuncs.com/gcr-sync/[镜像仓库名称]:[镜像版本号]
```

## 已同步镜像列表

| gcr镜像                   | 同步地址                                                     |
| ------------------------- | ------------------------------------------------------------ |
| prometheus-adapter:v0.9.1 | registry.cn-zhangjiakou.aliyuncs.com/gcr-sync/prometheus-adapter:v0.9.1 |
| metrics-server:v0.6.1     | registry.cn-zhangjiakou.aliyuncs.com/gcr-sync/metrics-server:v0.6.1 |

