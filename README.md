

### 1、项目介绍





### 10、帮助文档

生成api代码go-ctl示例

```cmd
goctl api go --api ./app/usercenter/cmd/api/desc/usercenter.api  --dir ./app/usercenter/cmd/api -style gozero
```

生成proto代码go-ctl示例

```cmd
goctl rpc protoc ./pb/usercenter.proto --go_out=. --go-grpc_out=. --zrpc_out=. -style goZero     
```


根据sql文件生成template代码
```cmd
goctl model mysql ddl --src user.sql --dir ../      -------------->  template: go init template #获取原始模板
```