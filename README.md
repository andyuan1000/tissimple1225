# tissimple1225
tissimple1225

# Usage

## 启动项目
```shell
mvn tis:run
```
也可以在idea中通过debug模式启动以上名来来测试插件
## 清除本地执行缓存

TIS插件启动过程中会在本地user_home目录中创建名为`tis_tmp`的目录，存放一些启动所需要的依赖文件，测试完毕之后可执行一下命令将缓存目录清除
```shell
mvn tis:clean
```

