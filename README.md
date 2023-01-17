# simple-admin-example-api
Ent api 生成例子

# 生成命令

```shell
goctls api new example --i18n=true --casbin=true --goZeroVersion=v1.4.3 --toolVersion=v0.1.6 --transErr=true --moduleName=github.com/suyuan32/simple-admin-example-api --port=8081

goctls api proto --proto=/home/ryan/GolandProjects/simple-admin-example-rpc/example.proto --style=go_zero --api_service_name=example --rpc_service_name=example --o=./ --model=Teacher --rpc_name=Example --grpc_package=github.com/suyuan32/simple-admin-example-rpc/example

```

> 还需在 service context, config, etc 添加 ExampleRpc