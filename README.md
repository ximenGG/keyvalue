# keyvalue
Room replace SharedPreferences
project build.gradle
allprojects {
    repositories {
        google()
        jcenter()
        maven {
            url "https://raw.githubusercontent.com/ximenGG/keyvalue/master"
        }
    }
}
app build.gradle       
dependencies {
    implementation "androidx.keyvalue:keyvalue:2.0.0"
}
