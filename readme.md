apply plugin: 'com.android.application'
apply from: 'https://raw.githubusercontent.com/bewant2be/androidbuild/master/version.gradle'

android {
    compileSdkVersion 23
    buildToolsVersion "23.0.1"

    defaultConfig {
        applicationId "com.aa.bb.cc"
        minSdkVersion 19
        targetSdkVersion 23
        versionCode gitVersionCode()
        versionName gitFullVersionTag() [v1.0.0  ->  v1.0.0 / v1.0.0-1-ga29f975]
        versionName gitVersionTag() [v1.0.0  ->  v1.0.0.0 / v1.0.0.2]
    }
}
    
    
    git tag -a v1.0.0 -m “v1.0.0”
    git push origin v1.0.0
    
    v1.0.0
    
    
    git add . && git commit -m "." && git push origin *
    v1.0.0-1-ga29f975
    
    
    