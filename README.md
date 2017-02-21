# JsonAnnotation
An annotation to load JSON objects for tests - the JOSN file are in stored in resource directories.  

# Usage

See example module
```
dependencies {
    compile fileTree(dir: 'libs', include: ['*.jar'])

    testCompile 'uk.co.sentinelweb:json-annotation:1.0.2'
}


repositories {
    jcenter()
    // todo still need this - hw to publish to main jcenter repo
    maven {
        url 'https://dl.bintray.com/sentinelweb/generic/'
    }
}
```
