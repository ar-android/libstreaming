# libstreaming

Building a RTSP library involves deep understanding of real time streaming protocols and good command over multiple java media APIs which is not easy for every beginner. 
Using this library can make your live more easier. This library from https://github.com/fyhertz/libstreaming


You can use by adding depedencies in your gradle build file `build.gradle`

```gradle
allprojects {
    repositories {
	maven { url 'https://jitpack.io' }
    }
}
```

And in you `app/build.gradle`
```gradle
dependencies {
     compile 'com.github.User:Repo:Tag'
}
```
