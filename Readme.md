#基于helloworld.proto生成pb文件
--
##命令: 
protoc --proto_path . --go_out=plugins=grpc:. ./helloworld.proto

#Mac平台搭建Grpc

## 安装protoc插件
brew install protobuf

## 安装grpc 和 protoc-gen-go 插件

go get -u google.golang.org/grpc

go get -u github.com/golang/protobuf/protoc-gen-go

参考资料：https://learnku.com/articles/38381