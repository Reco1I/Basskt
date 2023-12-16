# Basskt
[![](https://jitpack.io/v/Reco1I/Toolkt.svg)](https://jitpack.io/#Reco1I/Basskt)

Basskt is an API of bindings for the BASS library on Android with the goal to simplify the development with BASS using the Kotlin's language features. 

Originally intended to be a module in the [rimu! project](https://github.com/Reco1I/rimu).

## Usage
In order to use this library in your project you need to add the dependency in your app's module `build.gradle`.
```kts
dependencies {
    implementation("com.github.Reco1I:Basskt:1.0.1")
}
```

Make sure to have Maven and Jitpack repository declared on the root `settings.gradle`.
```kts
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        mavenCentral()
        maven {
            setUrl("https://jitpack.io")
        }
    }
}
```

Alternatively you can clone the repository and add the project as a library module in your app.
