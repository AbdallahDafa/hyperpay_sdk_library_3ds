# HyperPay SDK Implemnation Library
# Installer File AAR "ipworks3ds_sdk.aar" by implementaion dependence

## Step 1 : allow download library 

* Add JitPack to your build.gradle (Project-level)
gradle
 
```groovy

allprojects {
    repositories {
        google()
        mavenCentral()
        maven { url 'https://jitpack.io' }
    }
}
```
in newer Gradle versions (settings.gradle or settings.gradle.kts), make sure JitPack is added like this:
gradle

```groovy
dependencyResolutionManagement {
    repositories {
        google()
        mavenCentral()
        maven { url 'https://jitpack.io' }
    }
} 

```
 

-----

-----

## Step 2 : Install sdk in your project

### implementation to build.gradle depenences 
``` 
    implementation 'com.github.AbdallahDafa:hyperpay_sdk_library_3ds:v1.0.32' 
    implementation 'com.github.AbdallahDafa:hyperpay_sdk_library_3ds:1.0.32:3ds@aar'
```


### Testing Installing without SDK
* in android/app/build.gradle file add in dependency :

* this version have no .aar files, means just for testing , try in code use class "TestHyperPay.getName();"
```

```
or using latest version number

* after install trying to get name of testin
```
        TestHyperPay3Ds.getName();
```

# HyperPayLibraryAARFileMsa
# hyperpay_sdk_library_3ds
