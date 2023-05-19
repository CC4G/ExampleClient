# ExampleClient
一个以 CC4G 为开发环境的示例 Minecraft 客户端

cmd输入一下指令
```
./gradlew ideaRuns
```
构建环境

build.gradle文件里面的
```gradle
cc4g {
    gameVersion = '1.8.9'
    cc4g_client_api = true
}
```
代码块可以修改

参照列表
```
gameVersion 游戏版本(支持1.12.2和1.8.9其他就不支持了)
cc4g_client_api 是否引入配套api，可选，不引入也没事，只要你写端技术够硬就行
```
