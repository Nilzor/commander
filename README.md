## Commander — set of reactive functions for cli tools.

Commander provides functions to work with processes, files and other things useful for cli tools like [Swarmer](https://github.com/gojuno/swarmer) and [Composer](https://github.com/gojuno/composer).

Modules:

* [os](os/) — functions to work with processes and files on different Operating Systems.
* [android](android/) — functions to work with Android SDK Tools like adb, avdmanager, sdkmanager.

## Changes in this fork

This is a fork of [gojuno/commander](https://github.com/gojuno/commander). Changes in this fork compared to gojuno's version:

- Windows support by using proper `Path.Separator 

### Download

Commander is available on bintray. Add this repo to your gradle list:

```groovy
     repositories {
        // (other repos here)
        maven {
            url  "https://dl.bintray.com/nilzor/maven"
        }
    }
```

...then in your application

```groovy
compile 'com.nilzor.commander:os:0.2.1'
compile 'com.nilzor.commander:android:0.2.1'
```

All the releases and changelogs can be found on [Releases Page](https://github.com/gojuno/commander/releases).

### How to build

Dependencies: you only need `docker` and `bash` installed on your machine.

```console
bash ci/build.sh
```

## License

```
Copyright 2017 Juno, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

[spoon]: https://github.com/square/spoon
[test sharding]: https://developer.android.com/topic/libraries/testing-support-library/index.html#ajur-sharding
