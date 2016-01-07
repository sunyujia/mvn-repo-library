# mvn-repo-library


## Usage
###in your top-level build file

```java
buildscript {
    repositories {
        maven { url "https://raw.githubusercontent.com/sunyujia/mvn-repo-library/master/released" }
        jcenter()
    }
    dependencies {
        classpath 'com.android.tools.build:gradle:1.5.0'
    }
}
```
###in your module build file

```java
dependencies {
    compile 'com.yunzhanghu:library:1.0'
}
```





