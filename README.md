# core-library

Gradle Project<br />
![image](https://cloud.githubusercontent.com/assets/18477507/26244640/be1f9534-3cba-11e7-8c5a-dbb65291f11b.png)
<br />
<code>allprojects {</code><br />
<code>repositories {</code><br />
<code>jcenter()</code><br />
<code>maven { url 'https://jitpack.io' }</code><br />
<code>}</code><br />
<code>}</code><br />

----------------------------------------------------------------------------------------------------------------------------
Gradle App<br />
![image](https://cloud.githubusercontent.com/assets/18477507/26244594/82bb8fd4-3cba-11e7-824f-e70a8ca7847d.png)

<code>def daggerVersion = '2.10'</code><br />
<code>def androidAnnotationVersion = '4.2.0'</code><br />
<br />
<code>dependencies {</code><br />
<code>    compile 'com.github.titibok:core-library:0.1.0'</code><br />
<code>    annotationProcessor "com.google.dagger:dagger-android-processor:$daggerVersion"</code><br />
<code>    annotationProcessor "com.google.dagger:dagger-compiler:$daggerVersion"</code><br />
<code>    annotationProcessor "org.androidannotations:androidannotations:$androidAnnotationVersion"</code><br />
<code>}</code><br /><br />
