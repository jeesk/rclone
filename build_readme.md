1. 构建linux和windows 需要指定[cross-compile.go] 的tags 为cmount
2. 构建darwin平台需要开启cgo,并且安装osxfuse才能构建,tags 也需要指定为cmount