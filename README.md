# core-library
### Gradle Project<br />
![image](https://cloud.githubusercontent.com/assets/18477507/26244640/be1f9534-3cba-11e7-8c5a-dbb65291f11b.png) <br />
### Code:
```java
allprojects {
    repositories {
        jcenter()
        maven { url 'https://jitpack.io' }
    }
}
```

----------------------------------------------------------------------------------------------------------------------------
### Gradle App<br />
![image](https://cloud.githubusercontent.com/assets/18477507/26244594/82bb8fd4-3cba-11e7-824f-e70a8ca7847d.png) <br />
### Code:
```java
def daggerVersion = '2.10'
def androidAnnotationVersion = '4.2.0'
dependencies {
    compile 'com.github.titibok:core-library:0.1.0'
    annotationProcessor "com.google.dagger:dagger-android-processor:$daggerVersion"
    annotationProcessor "com.google.dagger:dagger-compiler:$daggerVersion"
    annotationProcessor "org.androidannotations:androidannotations:$androidAnnotationVersion"
}
```
