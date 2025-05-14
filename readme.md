# 集成
## 1. 在root's build.gradle中加入Jitpack仓库
```
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```

## 2. 在app's build.gradle中添加依赖
```
dependencies {
    ...
    保持最新版
    implementation 'com.github.yvws:QuickPlayer:+'
    或者指定具体版本
    implementation 'com.github.yvws:QuickPlayer:1.0.1'
}
```
