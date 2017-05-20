# core-library      version:0.1.0
### Gradle Project<br />
![image](https://cloud.githubusercontent.com/assets/18477507/26244640/be1f9534-3cba-11e7-8c5a-dbb65291f11b.png)
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
![image](https://cloud.githubusercontent.com/assets/18477507/26272502/4970efb4-3d44-11e7-9338-e8183929df57.png)
### Code:
```java
def daggerVersion = '2.10'
def androidAnnotationVersion = '4.2.0'
dependencies {
    testCompile 'junit:junit:4.12'
    compile 'com.github.titibok:core-library:0.1.0'
    annotationProcessor "com.google.dagger:dagger-android-processor:$daggerVersion"
    annotationProcessor "com.google.dagger:dagger-compiler:$daggerVersion"
    annotationProcessor "org.androidannotations:androidannotations:$androidAnnotationVersion"
}
```
