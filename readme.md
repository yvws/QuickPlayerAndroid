# integration
## 1. Add the Jitpack repository in root's build.gradle
```
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```

## 2. Add dependencies in app's build.gradle
```
dependencies {
    ...
    // Keep the latest version
    implementation 'com.github.yvws:QuickPlayerAndroid:+'
    
    // Or specify a specific version
	implementation 'com.github.yvws:QuickPlayerAndroid:1.1.2'
}
```