# keyvalue
Room replace SharedPreferences

# project build.gradle
```
buildscript {
    ext.kotlin_version = '1.5.0-M1'
    repositories {
        google()
        jcenter()
    }
    dependencies {
        classpath "com.android.tools.build:gradle:4.1.2"
        classpath "org.jetbrains.kotlin:kotlin-gradle-plugin:$kotlin_version"
    }
}

allprojects {
    repositories {
        google()
        jcenter()
        maven {
            url "https://raw.githubusercontent.com/ximenGG/keyvalue/master"
        }
    }
}
```
# app build.gradle       
```
dependencies {
    implementation "androidx.keyvalue:keyvalue:2.0.0"
}
```
