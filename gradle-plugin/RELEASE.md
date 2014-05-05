BINTRAY GRADLE PLUGIN RELEASE NOTES
===================================

Version 1.3 - Roadmap
---------------------
* [ISSUE #2](https://github.com/ysb33r/bintray/issues/2) - Support for uploading snapshots to oss.jfrog.
* [ISSUE #1](https://github.com/ysb33r/bintray/issues/1) - Transparent integration in repositories so that snapshots and production are automatically switched between oss.jfrog and Bintray.
* [ISSUE #3](https://github.com/ysb33r/bintray/issues/3) - Ability to create packages if they don't exist on Bintray. (via a configurable option).
* [ISSUE #4](https://github.com/ysb33r/bintray/issues/4) - Ability to auto-publish (via a configurable option).
* [ISSUE #5](https://github.com/ysb33r/bintray/issues/5) - Add generation of MD5s when uploading to Generic Bintray repository

Version 1.2
-----------
* Fixed a critical bug in 1.1 that affected uploading to generic Bintray repositories

Version 1.1 (Don't use this version)
-----------
* Added support for uploading to generic bintray repositories via the ```BintrayGenericUpload``` task

Version 1.0
-----------
* Now supports Bintray V1 API.
* Dropped ```JCenter()``` from the codebase as Geadle now nat8vely supports ```jcenter()```.
* Dropped ```Bintray``` class as it's only function was to shorted the typing of Bintray repositories.

Version 0.0.9 and earlier
-------------------------
* Moved Bintray code to it's own repository. Earlier code lived [here](https://github.com/ysb33r/Gradle/tree/RELEASE_0_0_9/bintray).
* Support uploading to Bintray.
* Support for Maven and Ivy style as part of the uploadArchives.